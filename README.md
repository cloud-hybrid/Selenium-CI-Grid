<<<<<<< HEAD
## Usage ##

1. Start the [development server](https://github.com/cloud-hybrid/ui-template)
   relative to the [root repository](https://github.com/cloud-hybrid/ui-template)
    - `npm run start`
2. Start the [Selenium-Grid Server](https://github.com/cloud-hybrid/grid)
3. Install dependencies if applicable
    - `npm install .`
4. Run the specification test(s)
    - `npm test`

**Note** - Tests cannot be run on a `localhost` host; the target e2e target must
be publicly resolvable.

## Commands ##

- `npm run compile` - compile the ES6 Babel into the `/lib` directory
=======
# Selenium + CI-CD Pipeline POC #

## Usage ##

### Setup ###

```bash
python3 -m venv .venv

source .venv/bin/activate

python3 -m pip install --requirement requirements.txt
```

### Selenium Grid ###

```bash
docker-compose --file ./local/Selenium-Grid-Recording.Yaml up
```

### Local Runtime ###

```bash
python3 -m src
```

## Teardown ##

### Selenium Grid ###

```bash
docker-compose --file ./local/Selenium-Grid-Recording.Yaml down
```
>>>>>>> 5b72e5a1446e959e9c1ccd599f01939ca953726e
