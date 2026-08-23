import base64, json
content = open('/workspace/dumps/workspace/LUFFY/README.md', encoding='utf-8').read()
print(base64.b64encode(content.encode()).decode())
