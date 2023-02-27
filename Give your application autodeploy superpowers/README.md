## Give your Application Auto-Deploy Superpowers

In this project, I proved my mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Project Submission

For my submission, I provided the following:

- A text file named `urls.txt` including:
  1. Public Url to my GitHub repository (not private) [URL01](./urls.txt)
  1. Public URL for my S3 Bucket (aka, my green candidate front-end) [URL02](./urls.txt)
  1. Public URL for my CloudFront distribution (aka, my blue production front-end) [URL03](./SUBMISSION%20SCREENSHOTS/URL03_SCREENSHOT.png)
  1. Public URLs to deployed application back-end in EC2 [URL04](./SUBMISSION%20SCREENSHOTS/URL04_SCREENSHOT.png)
  1. Public URL to my Prometheus Server [URL05](./SUBMISSION%20SCREENSHOTS/URL05_SCREENSHOT.png)
- My screenshots in JPG or PNG format, named using the screenshot number listed in the instructions.
  1. Job failed because of compile errors. [SCREENSHOT01](./SUBMISSION%20SCREENSHOTS/SCREENSHOT01.png)
  1. Job failed because of unit tests. [SCREENSHOT02](./SUBMISSION%20SCREENSHOTS/SCREENSHOT02.png)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03](./SUBMISSION%20SCREENSHOTS/SCREENSHOT03.png)
  1. An alert from one of my failed builds. [SCREENSHOT04](./SUBMISSION%20SCREENSHOTS/SCREENSHOT04.png)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05](./SUBMISSION%20SCREENSHOTS/SCREENSHOT05.png)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06](./SUBMISSION%20SCREENSHOTS/SCREENSHOT06.png)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07] (./SUBMISSION%20SCREENSHOTS/SCREENSHOT07.png)
  1. Successful promotion job. [SCREENSHOT08](./SUBMISSION%20SCREENSHOTS/SCREENSHOT08.png)
  1. Successful cleanup job. [SCREENSHOT09](./SUBMISSION%20SCREENSHOTS/SCREENSHOT09.png)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10](./SUBMISSION%20SCREENSHOTS/SCREENSHOT10.png)
  1. Screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11](./SUBMISSION%20SCREENSHOTS/SCREENSHOT11.png)
  1. Screenshot of an alert that was sent by Prometheus. [SCREENSHOT12](./SUBMISSION%20SCREENSHOTS/SCREENSHOT12.png)

- [presentation.pdf](./presentation.pdf) contains a power point presentaion used in selling CI/CD to non-technical members of my team assuming a real world scenerio

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
