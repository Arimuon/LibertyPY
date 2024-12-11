> [!IMPORTANT]\
> **Unreleased**, hoping for late December 2024 release.



---------

# LibertyPY
A Python API wrapper for the ER:LC API.

> [!IMPORTANT]\
> PLACEHOLDER

## Capabilities:
- [x] Run ER:LC Commands Remotely
- [x] Show Server Information
- [x] Show Current Players
- [x] Show Join Logs
- [x] Show Queue Information
- [x] Show Kill logs
- [x] Show Command Logs
- [x] Show Mod Calls
- [x] Show Banned Players
- [x] Show Current Vehicles
- [x] Dynamic Rate Limiting

## Installation
First you need to install the package.

```
pip install PLACEHOLDER
```

## Setup
Setup is easy:

```python
PLACEHOLDER CODE BLOCK
```

Now you can start using the API - here are some examples:

```python
PLACEHOLDER CODE BLOCK
```
### Classes and their methods:

#### `Remote Commands`
##### Create an instance ( command_api = Command(base_url, server_key) )
- `command_api.send_command(command)`

#### `Logs`
- `get_join_logs()`
- `get_command_logs()`
- `get_kill_logs()`
- `get_bans()`
- `get_mod_calls()`

#### `Information`
##### Create an instance ( info_api = Information(base_url, server_key) )
- `info_api.get_server_info()`
- `info_api.get_players()`
- `info_api.get_queue()`
- `info_api.get_vehicles()`


## Links
### [LibertyPY Documentation (W.I.P)](https://about:blank/)
### [Python Package (W.I.P)](https://about:blank/)
### [PRC API Documentation](https://apidocs.policeroleplay.community/reference/api-reference)


## Credits
Head Developer / Project Lead - [Arimuon](https://discord.com/users/1148923243097497600)

Collaborator - [Yodmin](https://discord.com/users/430480677058772992)

Documentation Inspiration - [0xRaptor](https://twitter.com/0xRaptorRblx)

Former Developer - [Missile05](https://discord.com/users/591298352344334388)
