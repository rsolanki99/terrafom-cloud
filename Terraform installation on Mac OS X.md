Terraform installation on Mac OS X using brews
We can install terraform on Mac OS X using brew command. Brew must first be installed on OS.

(base) Ravindra@ravindras-MacBook-Pro ~ % brew tap hashicorp/tap

Running `brew update --auto-update`...
==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Auto-updated Homebrew!
Updated 1 tap (homebrew/services).
No changes to formulae or casks.

==> Tapping hashicorp/tap
Cloning into '/opt/homebrew/Library/Taps/hashicorp/homebrew-tap'...
remote: Enumerating objects: 3204, done.
remote: Counting objects: 100% (238/238), done.
remote: Compressing objects: 100% (137/137), done.
remote: Total 3204 (delta 144), reused 183 (delta 101), pack-reused 2966
Receiving objects: 100% (3204/3204), 602.60 KiB | 4.63 MiB/s, done.
Resolving deltas: 100% (2008/2008), done.
Tapped 2 casks and 25 formulae (75 files, 818.6KB).
(base) Ravindra@ravindras-MacBook-Pro ~ % 
(base) Ravindra@ravindras-MacBook-Pro ~ % 
(base) Ravindra@ravindras-MacBook-Pro ~ % brew install hashicorp/tap/terraform
==> Fetching hashicorp/tap/terraform
==> Downloading https://releases.hashicorp.com/terraform/1.4.6/terraform_1.4.6_darwin_arm64.zip
################################################################################################# 100.0%
==> Installing terraform from hashicorp/tap
🍺  /opt/homebrew/Cellar/terraform/1.4.6: 3 files, 67.8MB, built in 4 seconds
==> Running `brew cleanup terraform`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> `brew cleanup` has not been run in the last 30 days, running now...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Removing: /Users/ravindra/Library/Caches/Homebrew/glib--2.74.6... (6.4MB)
Removing: /Users/ravindra/Library/Caches/Homebrew/jenkins-lts--2.375.3... (92.6MB)
Removing: /Users/ravindra/Library/Caches/Homebrew/libtiff--4.4.0_1... (1.2MB)

(base) Ravindra@ravindras-MacBook-Pro ~ % terraform version

Terraform v1.4.6
on darwin_arm64
