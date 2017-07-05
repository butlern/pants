python_requirement_library(
    name = "awscli104",
    requirements = [python_requirement("awscli==1.11.104")],
)

python_requirement_library(
    name = "awscli105",
    requirements = [python_requirement("awscli==1.11.105")],
)

python_binary(
    name = "aws104",
    entry_point = 'awscli.clidriver:main',
    dependencies = [":awscli104"]
)

python_binary(
    name = "aws105",
    entry_point = 'awscli.clidriver:main',
    dependencies = [":awscli105"]
)
