# 1 - Dat Cli
> A distributed **dat**a community

## Installation

```
$ npm install -g dat
```

## Sharing files

Let's make a quick pass through the [_features_](dat) of dat while using the CLI. We're going to share content, modifying, and syncronize it. We're also going to see
how to obtain specific content.

### dat share

Dat uses the command [share](dat#sharing-data) for sharing direcries.

### dat sync

The other half of the history for sharing files is downloading them. For this
we're going to look at the [clone](dat#downloading-data) _feature_. To know *what* data we are going to download we need an address, or _dat link_.

## Exercises

Form groups of two people :smiley_cat: :smile_cat:.

Next to this readme you'll find a directory `/cool_cats` with information
summing the importance of sharing :laughing:.

### 1- Share

One of you will be in charge of sharing our directory `/cool_cats`.

### 2 - Clone

The other person will be who clones the dat, using the link that is shown on
their computer.

### 3 - Create new content

One of you will create a new file inside the shared directory. We will call it
`top_secret.md`.

Here we leave you an idea for the content:

```
# TOP SECRET

> this archive will be destroyed in 5 seconds

And this is being disitrbuted :Cool:
```

### 4 - Get new content

To do this let's try the [pull](dat#updating-downloaded-archives) command.

### 5 - what happes if our computer changes the file?

:wink: sync

### Extra

1. What happens if we share the link with a new computer and only wnat to
   access the `top_secret.md` file?

### Tip

1. We can combine the option _spare_ with the special [`.datdownload`](dat#selecting-files) file.

