# What is Serverless ? 
![Slide2](https://github.com/user-attachments/assets/d154795c-f7b1-4aa8-ade8-37ae4d1bdd1e)
Serverless computing is a cloud computing execution model where the cloud provider automatically manages the infrastructure for running applications. This model allows developers to focus on writing code without worrying about server management tasks.

# Serverless vs. Server-Based Apps: Trade-Offs
| Factor                  | Serverless                                      | Server-Based                                      |
|-------------------------|--------------------------------------------------|---------------------------------------------------|
| **Scalability**         | Automatic and cost-efficient                    | Manual or predefined auto-scaling                |
| **Management**          | Minimal management and maintenance              | Full server management and maintenance           |
| **Performance**         | Variable performance and cold starts            | Consistent performance and custom optimization   |
| **Development**        | Faster deployment, microservices friendly      | Slower deployment, suited for complex architectures |
| **Costs**                | Pay-as-you-go, potentially variable costs       | Fixed costs, predictable for long-term usage     |
| **Security**            | Provider-managed, isolated environments         | Full control over security configurations        |
| **Complexity**          | Simple for small projects, complex at scale     | More setup needed, scales well for larger apps   |

# Serverless Computing Components
| Component       | Description                                                    | Example Providers                  | Example Usage                                    |
|-----------------|----------------------------------------------------------------|-------------------------------------|--------------------------------------------------|
| **FaaS**         | Function as a Service                                        | AWS Lambda, Google Cloud Functions | Event-driven tasks like API requests or file uploads |
| **BaaS**         | Backend as a Service                                          | Firebase, Auth0, AWS Amplify        | Managed services like databases and authentication |
| **API Gateway**  | Manages API requests and routes to serverless functions       | AWS API Gateway, Azure API Management | Creating, managing, and securing APIs            |

# Advantages of Serverless Computing
| Advantage            | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Reduced Costs**    | Pay only for the actual compute time and resources used.                     |
| **Automatic Scaling** | Automatically scales up or down based on demand.                            |
| **Focus on Code**    | Developers focus on writing code rather than managing infrastructure.       |
| **Quick Deployment**| Fast deployment and iteration of applications due to managed infrastructure. |
| **Improved Reliability** | High availability and fault tolerance managed by the cloud provider.       |

# Challenges of Serverless Computing
| Challenge            | Description                                                                       |
|----------------------|-----------------------------------------------------------------------------------|
| **Cold Starts**      | Latency when functions are invoked after being idle for a while.                 |
| **Vendor Lock-In**   | Ties applications to specific cloud providers and their services.                |
| **Complex Debugging**| Debugging can be complex due to the distributed nature of functions.             |
| **Limited Execution Time** | Functions often have limits on execution time and resources.                      |
| **Resource Limitations** | Constraints on memory, execution time, and concurrency for functions.             |


# Serverless vs. Traditional Server-Based Architectures
| Feature                 | Serverless Computing                                 | Traditional Server-Based Computing                  |
|-------------------------|-------------------------------------------------------|-------------------------------------------------------|
| **Management**          | Managed by the provider                              | Managed by the developer or DevOps team               |
| **Scaling**             | Automatic and on-demand                             | Manual or pre-configured auto-scaling                |
| **Cost**                | Pay-as-you-go based on usage                         | Fixed costs for server capacity and uptime           |
| **Performance**        | Variable, with potential cold start latency         | More consistent performance                           |
| **Development Speed**  | Faster due to reduced infrastructure management      | Slower due to server setup and maintenance           |
| **Flexibility**        | Limited flexibility due to predefined functions      | Greater flexibility for custom configurations         |

# Popular Serverless Services
| Cloud Provider | Serverless Service             |
|----------------|---------------------------------|
| **AWS**         | AWS Lambda, API Gateway, DynamoDB |
| **Google Cloud**| Google Cloud Functions, Firebase |
| **Microsoft Azure** | Azure Functions, Azure Logic Apps |
| **IBM Cloud**   | IBM Cloud Functions, IBM Cloud Databases |
| **Alibaba Cloud** | Alibaba Cloud Function Compute, API Gateway |

# When to Use Serverless
| Use Case              | Serverless      | Server-Based        |
|-----------------------|------------------|---------------------|
| **Microservices**    | Yes              | No                  |
| **High Traffic Apps** | No               | Yes                 |
| **Event-Driven Apps** | Yes              | No                  |
| **Cost Efficiency**  | Variable costs   | Fixed costs         |
| **Performance Needs**| Lower performance | Consistent performance |
| **Development Speed**| Faster           | Slower              |

# System Design Architecture
![system design architecture](https://github.com/user-attachments/assets/53950a26-a809-4791-9679-f084ad78aa09)

# Services I have Used 
![Slide4](https://github.com/user-attachments/assets/9f2ccbc2-a976-4f0e-aefd-c6ddabedaceb)

![Slide5](https://github.com/user-attachments/assets/88e7c094-98b7-4744-88ee-9caec59287fb)

![Slide6](https://github.com/user-attachments/assets/b12e6b89-b3e5-4e3e-9cde-f506d180f48a)

![Slide7](https://github.com/user-attachments/assets/47920c43-1f96-4e36-9945-d168c4f71c98)

![Slide8](https://github.com/user-attachments/assets/1719a79d-3983-4097-89b7-159f15f2d18c)

![Slide9](https://github.com/user-attachments/assets/cbec2c3e-136c-461c-b006-b8642658db73)

![Slide10](https://github.com/user-attachments/assets/29163343-692d-480b-9c24-f62afa4defb0)

![Slide11](https://github.com/user-attachments/assets/0cc13274-349b-49af-bc04-53c982b54911)




