# verified-commit-demo

This commit was by the boogeyman.

## Is [the Boogeyman's commit](https://github.com/rossabaker/verified-commit-demo/commit/0c5fd7167528de4ad1a935b42e22d907744d09c7) verified?

- Per GitHub in vigilant mode: no, because

  > No user is associated with the committer email.

- Per Git, yes, by @rossabaker, if you trust his PGP key.

  ```console
  $ git verify-commit 0c5fd7167528de4ad1a935b42e22d907744d09c7
  gpg: Signature made Mon Apr  6 14:47:03 2026 EDT
  gpg:                using EDDSA key 7544B00C573D705F6D90DD44735FF9FCC500DFF3
  gpg: Good signature from "Ross A. Baker <ross@rossabaker.com>" [ultimate]
  Primary key fingerprint: 904C 1537 33DB B010 6915  C0BD 975B E5BC 29D9 2CA5
       Subkey fingerprint: 7544 B00C 573D 705F 6D90  DD44 735F F9FC C500 DFF3
  ```


  
