# Early prototype for tags-based approach

**1. Clone this repository**

```bash
git clone git@github.com:iterative/gitops-object-registry.git
cd gitops-object-registry
```

**2. Create virtual environment named `venv`**
```bash
python3 -m venv venv
source venv/bin/activate
```
Install python libraries

```bash
pip install --upgrade pip setuptools wheel .
```

**3. Run**

```bash
bash showcase.sh
```

This will create `demo` branch and tags. Please don't push them back to this repo :)
To continue experimenting, call
```bash
gitops --help
```
to see functionality and read through demo example.
For this to work, you need to be locally in this repo.
Working with remote repo isn't supported yet.
