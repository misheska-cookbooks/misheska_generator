# Custom ChefDK generator cookbook

A custom ChefDK generator cookbook for https://github.com/misheska-cookbooks

## Usage

- Add the `--generator-cookbook` (or `-g`) parameter when you run
  `chef generate`:

```
chef generate cookbook hello -g ~/<path_to>/misheska_generator
````

OR

- Add a reference to this generator in your `knife.rb` or `~/.chef/config.rb`:

```
chefdk.generator_cookbook = '~/<path_to>/misheska_generator'
```

## Generate your own template

Run this command generate a skeleton code generator directory:

```
chef generate generator <my_generator_name>
```
