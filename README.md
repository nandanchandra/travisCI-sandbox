# Command To Run Docker Compose(dev+test)

1-->docker-compose up --build

# Command To Run Docker On Ngnix(Production)

1-->docker build -t produc:latest .

2-->docker run -p 5000:80 produc:latest