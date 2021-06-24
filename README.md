# Hello

My name is adsf

PullRequest:
  BodyTemplate: Hellou {{ .Metadata.Repository.Name }}
  Create: true
  Labels:
  - git-repo-sync
  Subject: Update from git-repo-sync
  TargetBranch: ""
Repository:
  CommitBranch: my-branch
  CommitMessage: |
    Update from ccremer/git-repo-sync

    long desc
  CreatePR: true
  DefaultBranch: main
  ForcePush: true
  Name: modulesync-slave-repo-1
  Namespace: ccremer
  SkipCommit: false
  SkipPush: false
  SkipReset: false
