# Quest 1:

## Git flow:
    - What is:
        - Many branches exists: master, develop, feature, release, and hotfix.
    - Pros:
        - Enable parallel development
        - Good at handling multiple version of code
        - Suitable for large project with multiple teams participate in and releases are less frequences
    - Cons:
        - Slowdown release process
        - Too many merge when promoting artifacts between environments/branches

## Github flow:
    - What is:
        - Fewer branches: master and feature/bugfix branches.
    - Pros:
        - More frequent release
        - Suitable for small teams and require faster feedback loop
    - Cons:
        - Not suitable for handling multiple version of code
        - Master branch can become unstable because it serves as both production and development branch

## Gitlab flow:
    - What is:
        - Use feature branches, no direct commits on master
        - All features and fixes go to the master branch while enabling production and stable branches
        - Everyone starts from master, and targets master
    - Pros:
        - Fewer branches than gitflow
        - Master branch is more stable than github-flow
        - Allowing the code to pass through internal environments before it reaches production
    - Cons:
        - Can become complex when it needs to maintain multiple version in production

## Reference:
https://about.gitlab.com/topics/version-control/what-is-gitlab-flow/
https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf
https://docs.gitlab.com/ee/topics/gitlab_flow.html
https://www.flagship.io/git-branching-strategies/


# Quest 2:
- [Super app repo](https://github.com/phuongnd96/super-app.git)

# Quest 3:
- [Terragrunt/Terraform repo](https://github.com/phuongnd96/Krystal-homework.git)
- [GKE Module Repo](https://github.com/phuongnd96/simple-gke.git)
- [GKE Services Repo](https://github.com/phuongnd96/gke-services.git)
