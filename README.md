> **reversed your mom**
```
class HeaderRetriever:
    @staticmethod
    def retrieve_headers(url):
        response = requests.head(url)
        return response.headers


class DiscordInfo:
    @staticmethod
    def get_username():
        return "arused"


class DiscordServer:
    def __init__(self, server_url):
        self.server_url = server_url

    def get_invite_link(self):
        return self.server_url


url = "https://github.com/Arused"
headers = HeaderRetriever.retrieve_headers(url)
for key, value in headers.items():
    print(f"{key}: {value}")

username = DiscordInfo.get_username()
print(f"Discord username: {username}")

server_url = ".gg/dast"
server = DiscordServer(server_url)
invite_link = server.get_invite_link()
print(f"Discord server invite link: {invite_link}")
```
