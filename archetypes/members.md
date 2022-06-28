---
name: "{{ replace .Name "-" " " | title }}"
image: "{{ .Name }}.png"
yearJoined: {{ .Date | dateFormat "2006" }}

# See content/members/_index.md for valid roles
role:

website:
twitterHandle:
googleScholar:
githubHandle:
---
