
# Discord.js V13 to V14 converter

This is a website that converts any discord.js code in V13 to discord.js V14 syntax


## Deployment

To deploy this project ust double click in the index.js



## Usage/Examples
Discord V13 code
```javascript
const embed = new MessageEmbed()
  .setAuthor({
    name: "Info",
    url: "https://example.com",
  })
  .setTitle("Example Title")
  .setURL("https://example.com")
  .setDescription("This is an example description. Markdown works too!\n\nhttps://automatic.links\n> Block Quotes\n```\nCode Blocks\n```\n*Emphasis* or _emphasis_\n`Inline code` or ``inline code``\n[Links](https://example.com)\n<@123>, <@!123>, <#123>, <@&123>, @here, @everyone mentions\n||Spoilers||\n~~Strikethrough~~\n**Strong**\n__Underline__")
  .addField(
    {
      name: "Field Name",
      value: "This is the field value.",
      inline: false
    },
    {
      name: "The first inline field.",
      value: "This field is inline.",
      inline: true
    },
    {
      name: "The second inline field.",
      value: "Inline fields are stacked next to each other.",
      inline: true
    },
    {
      name: "The third inline field.",
      value: "You can have up to 3 inline fields in a row.",
      inline: true
    },
    {
      name: "Even if the next field is inline...",
      value: "It won't stack with the previous inline fields.",
      inline: true
    },
  )
  .setImage("https://cubedhuang.com/images/alex-knight-unsplash.webp")
  .setThumbnail("https://dan.onl/images/emptysong.jpg")
  .setColor("#00b0f4")
  .setFooter({
    text: "Example Footer",
    iconURL: "https://slate.dan.onl/slate.png",
  })
  .setTimestamp();

await message.reply({ embeds: [embed] });
```

Output: Discord.js V14 code
```javascript
const embed = new EmbedBuilder()
  .setAuthor({ name({
    name: "Info",
    url: "https://example.com",
  })
  .setTitle("Example Title")
  .setURL({ url("https://example.com")
  .setDescription("This is an example description. Markdown works too!\n\nhttps://automatic.links\n> Block Quotes\n```\nCode Blocks\n```\n*Emphasis* or _emphasis_\n`Inline code` or ``inline code``\n[Links](https://example.com)\n<@123>, <@!123>, <#123>, <@&123>, @here, @everyone mentions\n||Spoilers||\n~~Strikethrough~~\n**Strong**\n__Underline__")
  .addFields(
    {
      name: "Field Name",
      value: "This is the field value.",
      inline: false
    },
    {
      name: "The first inline field.",
      value: "This field is inline.",
      inline: true
    },
    {
      name: "The second inline field.",
      value: "Inline fields are stacked next to each other.",
      inline: true
    },
    {
      name: "The third inline field.",
      value: "You can have up to 3 inline fields in a row.",
      inline: true
    },
    {
      name: "Even if the next field is inline...",
      value: "It won't stack with the previous inline fields.",
      inline: true
    },
  )
  .setImage({ url("https://cubedhuang.com/images/alex-knight-unsplash.webp")
  .setThumbnail({ url("https://dan.onl/images/emptysong.jpg")
  .setColor({ color("#00b0f4")
  .setFooter({ text({
    text: "Example Footer",
    iconURL: "https://slate.dan.onl/slate.png",
  })
  .setTimestamp({ time();

await message.reply({ embeds: [embed] });
```
## Authors

- Discord Server: [@Angel Development](https://discord.gg/RQ2NB2V9av)
- Github: [@NNKtv28](https://github.com/NNKTV28)
- Our All in one discord bot: [@Angel Multibot](https://discord.com/api/oauth2/authorize?client_id=1070273110722498561&permissions=8&scope=bot%20applications.commands)

