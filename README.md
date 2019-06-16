# EventGo Web
The repository for the EventGo web application

* [Contribute on the application](#contribute-on-the-application)
* [License](#license)

## Contribute on the application

### Prerequisites

 - [Git](https://git-scm.com/downloads) 
 - [Node.js®](https://nodejs.org/en/) version 12.4.x or later
 - [AWS Amplify CLI](https://github.com/aws-amplify/amplify-cli) configured with your credentials
 - [Angular CLI](https://cli.angular.io/) version 8.0.x or later

### Setup 

1. Clone this repository to a local folder
    ```bash
    git clone https://github.com/MartinTechy/eventgo-web.git
    ```
2. Move to the newly created repository
    ```bash
    mv ./eventgo-web
    ```
3. Install all the dependencies 
    ```bash
    npm install
    ```
4. Configure the Amplify project 
    ```bash
    amplify configure project
    ```
5. Pull the latest version of the amplify project
    ```bash
    amplify env pull
    ```
6. Start the project 
    ```bash 
    ng serve
    ```
7. Develop !


## License

Licensed under the [GPL-3.0](LICENSE) license.
