# Meng Website


## Usage

To commit a change and publish to the world
```bash
# From the main directory
$ hugo
$ cd public
$ git add .
$ git commit -m "commit msg"
$ git push origin master
```

Open a new story
```bash
# From main directory
$ hugo new stories/story_name.md
```

Open a new project
```bash
# From main directory
$ hugo new projects/project_name.md
```

When finished editing a post, remove the draft tag from the front matter or change it to false
```yaml
draft = false
```
