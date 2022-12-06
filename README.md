Brew Beer Company (located in Dublin): You can order beer tailored to your own liking online and you can go in store and purchase their own original beer flavours or even brew your own beer and wine. The store and website has been running for 15 years. 
IT Setup:
They have two on-premise servers that carry out a combination of functions. One server is a database server used for storing data and it also acts as a web server responsible for running their online store. The second server is for e-mails and filing. They are located in a small space with good ventilation and cabling in their IT office. Their local employees and workers outside of Dublin or Ireland communicate and exchange files and e-mails using Microsoft Exchange in their server and Microsoft Office. They have a computer at their store till for in store transactions. 
Recommendations:
I recommend incorporating the cloud in their IT infrastructure.  Instead of a server for emailing and filing they can use cloud-based services such as Gmail and Microsoft Office 365. It is easier to sync multiple devices and they can log in from anywhere. They also have built in security which prevents phishing attacks and malware. Using them makes it cheaper since it needs less management. 
Instead of a web server and putting in a lot of money upfront for the services, you can use the cloud where you pay for what you use so during off peak seasons they don’t waste money on the service that they don’t use and you can increase the service when there is high demand. Using a cloud provider such as AWS makes it viable since it is difficult to attack a major company so the website won’t go down easily. 
Since the store has been running for several years, their legacy system and applications is one drawback from moving the whole business to the cloud. It is difficult to migrate legacy systems and data to the cloud as it may cause service delays and data loss. Cloud APIs (application programming interface) can help free the data from the obsolete operating system and make updates easier for legacy applications. The company may choose to continue using their legacy systems because they still work and moving to the cloud may be too much of a hassle. However, they can do a hybrid of on-premise and cloud services. They can keep their data between their on-site database server and public cloud. If they want more control over their data and infrastructure it would be better to use Infrastructure as a Service. I recommend public over private cloud for this small business because the data doesn’t require high levels of security and private cloud needs more management.

# Docker Getting Started Tutorial

This tutorial has been written with the intent of helping folks get up and running
with containers and is designed to work with Docker Desktop. While not going too much 
into depth, it covers the following topics:

- Running your first container
- Building containers
- Learning what containers are running and removing them
- Using volumes to persist data
- Using bind mounts to support development
- Using container networking to support multi-container applications
- Using Docker Compose to simplify the definition and sharing of applications
- Using image layer caching to speed up builds and reduce push/pull size
- Using multi-stage builds to separate build-time and runtime dependencies

## Getting Started

If you wish to run the tutorial, you can use the following command after installing Docker Desktop:

```bash
docker run -d -p 80:80 docker/getting-started
```

Once it has started, you can open your browser to [http://localhost](http://localhost).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker-compose up
```

## Contributing

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or new content, please open an issue first before working on your idea. While we love input, we want to keep the tutorial  scoped to newcomers.
As such, we may reject ideas for more advanced requests and don't want you to lose any work you might
have done. So, ask first and we'll gladly hear your thoughts!
