# WorldWideShare (The File sharing Tool)

A simple shell script to upload files to [0x0.st](https://0x0.st) and get a shareable link.

## Overview

This script allows you to easily upload files to 0x0.st, a free file hosting service that provides a quick and straightforward way to share files online. The script uses `curl` to handle the file upload and returns a direct link to the uploaded file.

## Features

- Upload files to 0x0.st with a single command.
- Get a direct link to the uploaded file without any additional output.
- Simple and easy to use.

## Prerequisites

- A Unix-like operating system (Linux, macOS, etc.)
- `curl` installed on your system.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yatharthgeek/worldwide-share
   ```

2. Navigate to the project directory:

   ```bash
   cd worldwide-share
   ```

3. Make the script executable:

   ```bash
   chmod +x share.sh
   ```

4. (Optional) Create an alias for easier usage by adding the following line to your shell configuration file (e.g., `.bashrc` or `.zshrc`):

   ```bash
   alias share='~/path/to/your/repo/share.sh'
   ```

   Replace `~/path/to/your/repo` with the actual path to your cloned repository.

5. Reload your shell configuration:

   ```bash
   source ~/.bashrc
   ```

   Or for `zsh`:

   ```bash
   source ~/.zshrc
   ```

## Usage

To upload a file, use the following command:

```bash
share /path/to/your/file
```

The script will return a direct link to the uploaded file.

### About 0x0.st

[0x0.st](https://0x0.st) is a free file hosting service that allows users to upload files quickly and easily. It is designed for simplicity and efficiency, making it a popular choice for sharing files online without the need for an account or complex procedures. Here are some key features and details about 0x0.st:

#### Key Features

1. **Anonymous Uploads**: Users can upload files without creating an account, ensuring privacy and ease of use.

2. **Direct Links**: After uploading a file, users receive a direct link that can be shared with others. This link points directly to the file, making it easy to access.

3. **File Size Limit**: 0x0.st allows uploads of files up to a certain size (typically around 512 MB). This is suitable for most common file-sharing needs.

4. **Supported File Types**: The service supports a wide range of file types, including images, documents, archives, and more.

5. **No Expiration**: Files uploaded to 0x0.st do not expire, meaning they will remain available as long as the service is operational.

6. **Simple API**: 0x0.st provides a straightforward API for developers, allowing for easy integration into applications and scripts, such as the one you created.

7. **Minimalist Design**: The website has a clean and minimalist interface, focusing on functionality rather than unnecessary features.

#### How It Works

1. **File Upload**: Users can upload files via the website or through command-line tools like `curl`. The file is sent to the server, where it is stored temporarily.

2. **Link Generation**: Once the upload is complete, the server generates a unique URL for the uploaded file. This URL can be used to access the file directly.

3. **Accessing Files**: Anyone with the link can access the file without needing to log in or provide any personal information.

4. **Community-Driven**: The service is often used by developers, content creators, and anyone needing to share files quickly and efficiently.

#### Use Cases

- **Sharing Large Files**: Ideal for sharing large files that may not be suitable for email attachments.
- **Temporary File Hosting**: Useful for temporary file sharing during collaborations or projects.
- **Quick Access**: Provides a fast way to share files without the hassle of signing up for a file hosting service.
