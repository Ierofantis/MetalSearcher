# MetalSearcher

The best search tool for metal-archives https://www.metal-archives.com

Autocomplete search bar that get bands from an api that I have made and link them to their metal-archives profile

# Check it live!
https://metal-search.herokuapp.com

# Use the API for free!
https://super-archives.herokuapp.com/api/autosearch/{band_name}

# Example request for API

`GET request`

https://super-archives.herokuapp.com/api/autosearch/dark

`Response`

`[
    {
        "_id": "5f3569ca41f4833a70b31e2d",
        "title": "<a href='https://www.metal-archives.com/bands/Rotten_Dark/5042'>Rotten Dark</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b31e43",
        "title": "<a href='https://www.metal-archives.com/bands/Rove_in_the_Dark/3540452163'>Rove in the Dark</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b31f85",
        "title": "<a href='https://www.metal-archives.com/bands/Saedus_Darknight/105893'>Saedus Darknight</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b31fbe",
        "title": "<a href='https://www.metal-archives.com/bands/...and_Darkness_Follows/3540439329'>...and Darkness Follows</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b32012",
        "title": "<a href='https://www.metal-archives.com/bands/A_Darkened_Sea/49148'>A Darkened Sea</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b32027",
        "title": "<a href='https://www.metal-archives.com/bands/A_Light_in_the_Dark/3540468818'>A Light in the Dark</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b3216a",
        "title": "<a href='https://www.metal-archives.com/bands/Abysmal_Darkening/29915'>Abysmal Darkening</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b32241",
        "title": "<a href='https://www.metal-archives.com/bands/Artificial_Darkness/69552'>Artificial Darkness</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b3227d",
        "title": "<a href='https://www.metal-archives.com/bands/As_Darkness_Fell/3540407176'>As Darkness Fell</a>"
    },
    {
        "_id": "5f3569ca41f4833a70b325fc",
        "title": "<a href='https://www.metal-archives.com/bands/Clad_in_Darkness/16077'>Clad in Darkness</a>"
    }
]`
