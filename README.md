# ProtoShark Jupyter Notebook Docker
Docker image with ProtoShark, and jupyter-notebook installed

## Build Image
- `git clone git@github.com:jonathanburkert/protoshark_jupyter.git`
- `cd protoshark_jupyter`
- `docker build -t protoshark_jupyter .`

## Run
- `docker run -d --name protoshark_jupyter --privileged --net=host -p 127.0.0.1:8888:8888 protoshark_jupyter`
- You should now have port 8888 open on the lo interface, use a web browser to connect and the password is `password`

