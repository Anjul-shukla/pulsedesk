# Setup Steps

1. Install Hermes

2. Install Ollama

3. Pull model:
   ollama pull qwen2.5-coder:7b

4. Configure .env:

   * SLACK_BOT_TOKEN
   * SLACK_APP_TOKEN
   * GATEWAY_ALLOW_ALL_USERS=true

5. Start gateway:
   hermes gateway run --replace

6. Invite bot to Slack channel

7. Test:
   @ForgeBot hello
