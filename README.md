# GORILLA-CAMP
import discord
from discord.ext import commands

bot = commands.Bot(command_prefix='?')

@bot.command()
async def ping(ctx):
    await ctx.send('IDK IM NOT SMART')

bot.run('ODkxODg5OTA4NDI2MzYyOTIx.YVE7NA.BFfzcUvGB4YG869InN_ynPl3AIY')
