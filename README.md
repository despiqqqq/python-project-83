### Hexlet tests and linter status:


### Description
[SEO Page Analyzer](https://seo-page-analyzer-rx3z.onrender.com/) is a web tool to check Serch Engine Optimization support of a given URL.



### Requirement
* Python
* Poetry
* Postgres

### Installation
**Setting up enviroment**
```bash
git clone https://github.com/DREU007/seo-page-analyzer
cd seo-page-analyzer
make build
```

Configure .env in the root folder
```
cp .env_example .env
```

**Dev**
```bash
make dev
```

**Prod**
```bash
make start
```

*Additional functions are available in Makefile*
