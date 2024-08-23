- 👋 Hi, I’m @hymachikku
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
hymachikku/hymachikku is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Configure the AWS provider
provider "aws" {
  region = "eu-west-1"
}

# Create an EC2 instance
resource "aws_instance" "example" {
  ami           = "ami-785db401"
  instance_type = "t2.micro"
}
