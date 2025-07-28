# Noggi-XLScan
Recreation of Weatherscan Local in Viz; a version of Weatherscan that lasted from the late 1990s to the early 2000s.

(not to be confused with Weatherscan Local for web)

#### This is your first look at Project Noggi, our project aiming to bring older TWC graphics to the IntelliStar 2 family through VizRT.



>[!WARNING]
> This Viz design **must** be run on an IntelliStar 2 Jr only. Failure to follow this can result in the design having flaws or more likely, Viz crashing entirely.

> Please note that on most I2's, at **3:11 am**, it will kill the Viz process to prevent memory leaks. This will also stop the presentation. You can either turn off the **KillViz** process in **Task Scheduler**, but this isn't recommended due to memory leaks, or you can create a script that automatically recues after 3:11 am. A script like this will be made soon and put into the repository however.

# Credits

**astinkyroach** - Main Scene Designer

**COLSTER** - Template Design

**zachNet** - Tester

**Miceoroni** - Tester

# Inital Setup

### REQUIRES:

 - An IntelliStar 2 Jr
 - Data Encoder for the I2Jr (Noggi-XLScan works best wth MistWX-I2ME, but you can try other data encoders. Some might not work as well however.)
 - Constant stream of data (This can be accomplished with I2ME and most data encoders out there.)
 - 8 Locations in your Machine Product Config. This can be easily added by going to a website that provides the [weather codes](https://weather.codes/united-states-of-america/) the I2 uses; or by using the LFRecord file in your data encoder.

**1.** Once the .zip has been extracted, place the TWC and vizrt files in C:\Program Files\. **THIS WILL NOT OVERWRITE EXISTING FILES.**

**2.** In Internet Explorer go to localhost:9091; or whatever port you set the web panel to, and look for "**Load and Run Playlist**", and input the values shown in the **Flavors** section of this README.

**You're all set!** Open VLC, or any video playback software of your choice and open the network stream. You should see Noggi-XLScan running.

---------

Need help with setting this up? Join the [***mist weather media*** Discord](https://discord.gg/hV2w5sZQxz) and go to the star-support channel.

---------

Do you have experience with viz!artist 2.8, or how the TWC product XMLs work? You're welcome to submit any issues, pull requests, and more! **Thank you.**

# Flavors

- Flavor: wxscanXL
- *(RECOMMENDED)* Presentation ID: 1
- Duration: 9419


# Products

- Local Forecast
- Mini-Core (extra city forecast)
- Spanish Forecast
- Golf (partial)
- Health (partial)

# To-Do

- Add Aviation products (will be added when I2ME has airport support)
- Add more map products
