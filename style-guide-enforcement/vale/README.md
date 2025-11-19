# How to use Vale

To use vale in your project:

1. Install Vale. Check out [Vale Install](https://vale.sh/docs/install) docs for information on how to install Vale.

2. Create a `.vale.ini` file in your docs root repository.

3. Copy and paste your Vale configuration in your `.vale.ini`. Check out [Vale's config generator](https://vale.sh/generator) to create your base Vale configuration.

4. Change your current directory into the directory that has the `.vale.ini`.

```bash
cd style-guide-enforcement/vale
```

5. Sync your Vale configuration with this command:

```bash
vale sync
```

6. Run Vale against your documentation:

```bash
vale .
```
