# moodle-rds-asg-cloudformation

[![GitHub](https://img.shields.io/badge/GitHub-romarcablao-lightgrey)](https://github.com/romarcablao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-romarcablao-blue)](https://linkedin.com/in/romarcablao)

## What is moodle

Moodle is a very popular open source learning management solution (LMS) for the delivery of elearning courses and programs. It’s used not only by universities, but also by hundreds of corporations around the world who provide eLearning education for their employees. Moodle features a simple interface, drag-and-drop features, role-based permissions, deep reporting, many language translations, a well-documented API and more. With some of the biggest universities and organizations already using it, Moodle is ready to meet the needs of just about any size organization. [Read more...](https://moodle.org/)

## Instructions

1. Provision a RDS (either MySQL or MariaDB).
2. Take note of the credentials from your RDS instance [user] [password] [port] [host] [dbname]
3. Provision a Auto Scaling Group with Launch Config. This will spin up instances with initial install of docker and the image of moodle.
4. Wait until the CFN is completed. You may now setup and update your own moodle website.
5. Update themes and your good to go. Happy Deployment!

## References

1. [awslabs/aws-cloudformation-templates](https://github.com/awslabs/aws-cloudformation-templates)
2. [widdix/aws-cf-templates](https://github.com/widdix/aws-cf-templates)