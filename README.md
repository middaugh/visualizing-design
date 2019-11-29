
## An Exploration of the Cooper Hewitt's Poster Design Collection 

__INFO 590 Final Project__
__November 27, 2019__
__Esmé Middaugh__

For this project, I want to create an interactive timeline of the Cooper Hewitt’s (CH) poster collec- tion. Their API [1] gives in depth information for every item in their collection, including variables such as name, date acquired, date created, color palette, creator, image, etc, and I plan to visually encode these variables onto the timeline, giving a broad look at how poster design and the CH’s collection have changed over time.

## Motivation and Background 

While I admit that this project was initially conceived more out of a love for looking at the CH’s collection more than anything else, there are many important uses for the visualization, for both visitors to the museum in person/online and the museum itself. At a simplistic level, it could help visitors learn how they want to explore the posters on the website; the current site offers little in the way of navigation, so knowing how you might want to filter your results would be helpful.
Expanding this idea more broadly, a visualization could provide interesting insights into the CH’s collection. Aggregating the in-depth information available on each individual poster, you could give a view into what proportion of works collected at different points in the museum’s history were done by male vs female artists, or how the color palettes have changed throughout history. Ultimately this is an exploratory tool to gain both a better view of both the CH’s Poster Collection, and how posters as an artform have changed throughout history.
The value of visualization as a means of helping the public understand museum’s collections (and how the world has changed over time) is by no means a novel concept. Scholars have written about the need for temporal based museum visualization systems [2] and there is even a non- profit group dedicated in part to making museums’ data more freely accessible. The Museums Computer Group’s mission is “encouraging, improving and influencing best practice in the use of technology and digital platforms within the museums;” they recently had a call for participants to attend a workshop in Berlin, dedicated solely to a ‘data sprint,’ in other words, figuring out how to collectively “explore through data visualization and software development the role, history, and
1
social context of cultural assets in contemporary society”[3]. More and more museums themselves have been trying to find ways to give better access to their collections [4]. Some museums have specifically encouraged people to visualize their collections, such as the Tate Modern, who made their collection available via GitHub, and add links to visualizations that people create [5].
This interest in ‘cultural analytics’ has grown in recent years, with IPAM Hosting an entire con- ference on it in 2016 [6]. At said conference, Lindsay King gave a fascinating talk on the usage of the Vogue Archive for analytics. Among other things, she mentioned creating a tool that allowed users to filter covers by different colors, allowing people to see how the fashion color trends had changed over time [7]. This is not only a great example of how powerful cultural analytics can be, but also why the CH API is a good data choice; their color mapping palette (which is incorpo- rated into their API) was the basis for what King and her fellow scholars did on the Vogue project. Clearly, museums and scholars alike recognize the value of cultural analytics.



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
### First Attempt 

<iframe src="https://middaugh.github.io/visualizing-design/initial_viz.html"></iframe>


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/middaugh/visualizing-design/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
