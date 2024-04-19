# MailHog Docker Container

This project provides a Docker container configuration to quickly spin up a MailHog instance for local email testing and development purposes.

## What is MailHog?

MailHog is an email testing tool for developers. It allows you to capture and view emails sent by your application during development without actually sending them to real recipients. It's particularly useful for testing email functionality in applications without spamming your users or sending test emails to real addresses.

You can find more information about MailHog in the [official documentation](https://github.com/mailhog/MailHog).

## How to Use

To use this Docker container, make sure you have Docker installed on your system. Then, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/tallmancode/docker-mailhog.git
   ```

2. Navigate into the cloned directory:

   ```
   cd mailhog-docker
   ```

3. Run Docker Compose to spin up the MailHog container:

   ```
   docker-compose up -d
   ```

4. That's it! MailHog should now be running and accessible on `http://localhost:8025`. You can open this URL in your web browser to access the MailHog dashboard and view captured emails.

## Configuration

This Docker Compose setup comes with default configurations, but you can customize it to suit your needs. You can modify the `docker-compose.yml` file to change things like ports, volumes, or environment variables.

For detailed information on configuring MailHog, refer to the [official Docker Compose documentation](https://docs.docker.com/compose/) and the [MailHog documentation](https://github.com/mailhog/MailHog).

## Contributing

If you encounter any issues with this Docker container setup or have suggestions for improvements, feel free to open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
