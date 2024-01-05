---
title: Launching a New World
description: This guide will walk you through launching into a newly released world.
permalink: /Guides/World/
category: Guides
order: 202
---
* 
{:toc}

## Update Drone Dash
First we need to update Drone Dash to the latest version to get the latest worlds. Run the following command to update Drone Dash.
```bash
cd ~/drone-dash && git pull
```

## Launching into the New World
To launch into a specific world add the `world` argument to the launch command. For example to launch into `world_1`, run the following command.
```bash
roslaunch drone_dash world:=1
```

> Note: The original world is `world_0` i.e. the default value for the `world` argument is `0`.