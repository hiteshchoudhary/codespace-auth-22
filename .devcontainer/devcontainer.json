{
	"name": "Node.js",
	"image": "mcr.microsoft.com/devcontainers/javascript-node:16-bullseye",
	"features": {
		"ghcr.io/devcontainers/features/docker-from-docker:1": {}
	},

	// Features to add to the dev container. More info: https://containers.dev/implementors/features.
	// "features": {},

	// Use 'forwardPorts' to make a list of ports inside the container available locally.
	 "forwardPorts": [4000],

	// Use 'postCreateCommand' to run commands after the container is created.
	 "postCreateCommand": "npm install",

	// Configure tool-specific properties.
	 "customizations": {
		"vscode": {
			"extensions": [
				"esbenp.prettier-vscode",
				"rangav.vscode-thunder-client"
			],
			"settings": {
				"editor.fontSize": 32,
				"terminal.integrated.fontSize": 24
			}
			
		}
		
	 }

	// Uncomment to connect as root instead. More info: https://aka.ms/dev-containers-non-root.
	// "remoteUser": "root"
}
