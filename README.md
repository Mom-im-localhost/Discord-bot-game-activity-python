# Discord-bot-game-activity-python
я замечаю что у некоторых людей с этим проблеми так что пусть будет
@Bot.event
async def on_ready():
  while True:
    game = discord.Game("j,cry")
    await Bot.change_presence(status=discord.Status.idle,
    activity=game)
