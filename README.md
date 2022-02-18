# Code Standards

```bash
# install
cd ~/www
mkdir CodeStandards && cd CodeStandards
git clone git@github.com:johnshopkins/JHUCodeStandards.git JHU
phpcs --config-set installed_paths ~/www/CodeStandards/JHU

# make sure installation succeeded
phpcs -i
The installed coding standards are MySource, PEAR, PSR1, PSR12, PSR2, Squiz, Zend and JHU
```
