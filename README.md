# The very minimum cookbook for Chef

Traditionally, we are taught to use knife command to create a cookbook

```shell
knife cookbook create hello -o cookbooks
```

But it will generates lots of empty directories and nonsense .gitkeep files.

Forget all about `knife cookbook`.

All you need is only one file `recipes/default.rb` to compose a cookbook :)
