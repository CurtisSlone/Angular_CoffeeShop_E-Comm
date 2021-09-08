# CoffeeShop

### Development
This project was built using Angular 9.0.1, node.js 12.15.0

### Deployment
Docker

## Viewing and Running Application How To
### Requires Angular Cli v. 9
git clone git@github.com:CurtisSlone/Angular_CoffeeShop_E-Comm.git
cd Angular_CofeeShop_E-Comm
npm install

### To view for dev environment
ng serve --open

## Build for production
ng build --prod

### Dockerize (requires Docker and cli tools)
docker . -t coffeeshop -f Dockerfile
docker run -p 80:80 coffeeshop

