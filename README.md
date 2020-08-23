# Variables vs Environment Variables 

The **environment** provides a medium through which the shell process can get or set settings and, in turn, pass these on to its child processes.

The **environment** is implemented as strings that represent key-value pairs. If mulitple values are passed, they are separated by colon **(:)** characters.

**Environmental variables** are variables that are defined for the current shell and are inherited by any child or processes. Environmental variables are used to pass information into processes that are spawned from the shell. 

**Shell variables** are variables that are contained exclusively within the shell in which they were set or defined. They are often used to keep track of ephemeral data, like the current working directory. 


Creating variables in Linux 
```bash
name="Anais"
```

Displaying variable value 
```bash
echo $name
```

Exporting variables to our environment 
```bash
export name="Anais"
```

Checking our env 
```bash
env
```

## Making environment variables persistent
```bash
vi ~/.bashrc
```

Running `node app.js`
```
http://development.local:3000/posts
```

# Reverse Proxy 

## What is a reverse proxy?
- Reverse proxy protects web servers from attacks and can provide performance and reliability benefits. 
- A reverse proxy is a server that sits in front of web servers and forwards client (e.g. web browser) requests to those web servers. 
- Reverse proxies are typically implemented to help increase security, performance, and reliability. 

## What's a proxy server?
- A forward proxy, often called a proxy, proxy server, or web proxy, is a server that sits in front of a group of client machines. When those computers make requests to sites and services on the Internet, the proxy server intercepts those requests and then communicates with web servers on behalf of those clients (like a middleman).

## Why use a forward proxy?
- **To avoid state or institutional browsing restrictions** - Some governments, schools, and other organisations use firewalls to give their users access to a limited version of the Internet. 
