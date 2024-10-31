# python-template

## Usage

1. Install Copier using **one** of these methods ([docs](https://copier.readthedocs.io/en/v5.1.0/)):
   * [Rye](https://rye.astral.sh/): `rye install copier`
   * [pipx](https://pipx.pypa.io): `pipx install copier`
   * pip: `pip install --user copier`
2. Generate a project ([docs](https://copier.readthedocs.io/en/stable/generating/)): `copier copy gh:object-Object/python-template path/to/destination`
   * To generate a project in the current directory (ie. if you already created a directory for the project): `copier copy gh:object-Object/python-template .`
3. (Optional) If you generated the project with Rye, update the generated dependencies to the latest versions by running this command in the new project: `rye sync --update-all`
