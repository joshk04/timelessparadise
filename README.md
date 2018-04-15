{
    username:'Pixel Updates',
    avatar_url: "https://cdn.discordapp.com/attachments/299004474905722882/327326803553157120/pxls.png",
    embeds: {
      color: parseInt(palette[data.pixels[0].color]),
      title: "New Pixel",
      description: "A new pixel was placed!",
      fields: [{
        name: "Coordinates",
        value: `X: ${data.pixels[0].x}\nY: ${data.pixels[0].y}`
      }, {
        name: "Color ID",
        value: data.pixels[0].color
      }]
    }
  }
