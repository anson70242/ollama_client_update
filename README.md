# Ollama Client Configuration Helper  

If you use Ollama with a client, every time you update Ollama, you need to manually add environment variables for it to work. This can be annoying and repetitive.  

This repository provides a simple shell script that automatically updates the configuration file.  
With just one command, you can automatically configure Ollama correctly with the update.

## Installation  
1. Clone this repository:  
```sh
git clone https://github.com/anson70242/ollama_client_update.git
```
2. Move the script to a system-wide location and make it executable:
```sh
sudo mv ollama_client_update/update_ollama /usr/local/bin/
```
```sh
sudo chmod +x /usr/local/bin/update_ollama
```

## Usage
If Ollama needs an update, run:
```sh
update_ollama
```
This will apply the required configuration automatically.

## License
This project is open-source and available under the MIT License.
