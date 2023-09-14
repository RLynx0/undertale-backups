# Rooms
This is a collection of normally inaccessible rooms.
The hightlight here is obviously Entry Number 17, 
but there are a few cool debug rooms in here too!

---

# What is this?
In this repo, I aim to collect as many 
Undertale-save files as possible. They're intended 
for public use and aimed to make reexperiencing 
various moments of the game easier.

## How to
To use this, you can either search through the 
branches and commits right from Github, or, if 
you're familiar with git or a git-ui, clone the 
repo so you have access to all timelines locally, 
whenever you may need them.

Depending on what Platform you are playing on, 
Undertale stores it's data in one of these locations:
| Platform | Path                                                   |
| -------- | ------------------------------------------------------ |
| Windows  | `%LOCALAPPDATA%\UNDERTALE`                             |
| Mac      | `~/Library/Application Support/com.tobyfox.undertale/` |
| Linux    | `~/.config/UNDERTALE/`                                 |

Navigate there, backup your own files to somewhere 
else, and paste the files from the commit of your 
choosing in. Optionally, you can clone my repo into 
that location, and maybe even set up an upstream, 
so you can pull any new branches or commits I might 
add. If you choose to go this path, you can also 
make a custom branch to store your own save files! :)

## Please note
This repository is a work in progress. 
I may not ever scrape together every single possible 
route in here, but I will come back to it every now 
and then. For now, I hope you enjoy breaking Flowey's 
mind with me, as we use powers far greater than 
he could fathom! Have fun!

## Repository structure
For each line of choices I have played through, 
there is a unique git branch in this repository. 
The two large routes, pacifist and genocide, 
originate directly from the master-branch. All 
other routes are derived from one of the two. 
Additionally, I have a few branches to make 
experiencing unaccessable rooms and fun events 
easier.

### Commits
In the major routes I aim to have a commit 
for each save point or sometimes larger events 
like having defeated a boss, or being shortly 
before, I don't know, the Papyrus-date for 
instance.

I'm not quite so vigilant in the neutral runs, 
I tend to only commit important save points 
like the ones before bosses or right at the 
end of the game.

### Naming
The neutral routes are named based on which 
monsters I killed. `neutral-kill_toriel` maps 
to a route where toriel is the _only_ monster 
I killed, `neutral-kill_toriel_papyrus` maps 
to a route where only toriel and papyrus are 
killed and so on. I use the keyword `minor` 
to indicate having killed monsters other than 
the (mini)bosses.

On the other hand, `genocident`-branches map 
to a failed genocide-run, where I spared one 
or more monsters along the way. These are 
named similarly to the more tame neutral routes, 
`genocident-spare_toriel` is a route where I 
spared _only_ toriel. I use region names like 
`snowdin` to indicate not having killed all 
monsters in these areas.
