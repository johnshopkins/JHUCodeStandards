# Code Standards

```bash
# install
cd ~/www
mkdir CodeStandards && cd CodeStandards
git clone git@github.com:johnshopkins/JHUCodeStandards.git
phpcs --config-set installed_paths ~/www/CodeStandards/JHUCodeStandards

# make sure installation succeeded
phpcs -i
```
