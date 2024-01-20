# Setup Kyverno Locally

1. Clone
2. F1 -> Open in WSL
3. Ctrl + Shift + p
4. Reopen in Container
5. `apt install make`
6. `make install-tools`
// if it doestn't work, close vs code and do step 6 again.
7. `make build-kyverno`
8. git remote add upstream  https://github.com/kyverno/kyverno
9. git fetch upstream --tags
