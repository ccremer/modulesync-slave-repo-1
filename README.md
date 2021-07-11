# Hello

My name is adsf

PullRequest:
  BodyTemplate: Hellou {{ .Metadata.Repository.Name }}
  Create: false
  Labels:
  - greposync
  Subject: Update from greposync
  TargetBranch: ""
Repository:
  CommitBranch: my-branch
  CommitMessage: |
    Update from ccremer/greposync

    long desc
  DefaultBranch: main
  ForcePush: true
  Name: modulesync-slave-repo-1
  Namespace: ccremer
  SkipCommit: false
  SkipPush: false
  SkipReset: false
