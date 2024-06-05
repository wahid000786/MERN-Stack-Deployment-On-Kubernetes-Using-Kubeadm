# MERN Stack Blog Application on Kubernetes

## Project Description

This project demonstrates Deploying a MERN (MongoDB, Express, React, Node.js) stack blog application on a Kubernetes cluster using Kubeadm. The application consists of three main components: the frontend, backend, and MongoDB database, each running on different pods. 

## Project Structure

- **Frontend**: React application running on port 5173.
- **Backend**: Node.js application running on port 8080.
- **Database**: MongoDB container.

## Prerequisites

- Kubernetes cluster set up using Kubeadm.
- Docker installed on all nodes.
- kubectl configured to interact with the cluster.

## Deployment Steps

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/mern-k8s-blog.git
cd mern-k8s-blog
