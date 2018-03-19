# YouTube Scrape

A YouTube search scraping API

## Get search results
The base url to get search results, is as follows:<br>
```
http://youtube-scrape.herokuapp.com/api/search
```
The url query options are as follows:
<table>
  <thead>
    	<tr>
        <th>Query</th>
        <th>Type</th>
        <th>Description</th>
    	</tr>
  </thead>
  <tbody>
		<tr>
        <td>q</td>
        <td>String</td>
        <td>YouTube search query</td>
    	</tr>
    	<tr>
        <td>page</td>
        <td>Number</td>
        <td>The page of YouTube search results</td>
    	</tr>
  </tbody>
</table>

Note that if no page is specified the default is 1
Here is an example call:
```
http://youtube-scrape.herokuapp.com/api/search?q=herman%20fassett&page=1
```
Example output:
```
{
  "results": [
    {
      "video": {
        "title": "Sunrise - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=7EY2qJ9vQHI",
        "duration": "2:36",
        "snippet": "",
        "upload_date": "1 year ago",
        "thumbnail_src": "http://i.ytimg.com/vi/7EY2qJ9vQHI/mqdefault.jpg",
        "views": "120"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Exiled - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=fnpvgyuooPs",
        "duration": "2:01",
        "snippet": "",
        "upload_date": "1 year ago",
        "thumbnail_src": "http://i.ytimg.com/vi/fnpvgyuooPs/mqdefault.jpg",
        "views": "104"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "After Harvest - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=WGYqoa0iePs",
        "duration": "2:13",
        "snippet": "",
        "upload_date": "2 months ago",
        "thumbnail_src": "http://i.ytimg.com/vi/WGYqoa0iePs/mqdefault.jpg",
        "views": "27"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "A Winter Day - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=Za7OZ6MsmjU",
        "duration": "3:24",
        "snippet": "",
        "upload_date": "1 year ago",
        "thumbnail_src": "http://i.ytimg.com/vi/Za7OZ6MsmjU/mqdefault.jpg",
        "views": "60"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "The Path To Freedom - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=nv7xf0MUFzw",
        "duration": "3:31",
        "snippet": "",
        "upload_date": "11 months ago",
        "thumbnail_src": "http://i.ytimg.com/vi/nv7xf0MUFzw/mqdefault.jpg",
        "views": "91"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Snowfall - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=d5JAd7N3mBY",
        "duration": "2:52",
        "snippet": "",
        "upload_date": "1 month ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "27"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Darkness Comes (WOT Fan Music) - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=p3REFOpIx6c",
        "duration": "3:22",
        "snippet": "This piece is kind of playing around with a very different style than I have ever done before, and I have also been reading the ...",
        "upload_date": "1 week ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "6"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Our Barren Lands (Cello) - Herman Fassett",
        "url": "https://www.youtube.com/watch?v=N2RhnMPbOPc",
        "duration": "3:05",
        "snippet": "I actually had this cello melody sort of lying around and thought I'd pull it out really quickly for this contest: ...",
        "upload_date": "1 month ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "14"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Brightness Davar - Sanderson Fan Music",
        "url": "https://www.youtube.com/watch?v=s81qJvX5qrI",
        "duration": "7:02",
        "snippet": "Here's a new piece I've written which is a fan piece for Brandon Sanderson's Stormlight Archive books. This follows the events that ...",
        "upload_date": "10 months ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "393"
      },
      "uploader": {
        "username": "Herman Fassett",
        "url": "https://www.youtube.com/channel/UCsOlslmdfxy6aG3O9Xkh5kA",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Kaffe Fassett on Patchwork and Quilting",
        "url": "https://www.youtube.com/watch?v=b0_bbkMOvXk",
        "duration": "4:29",
        "snippet": "Iconic textile designer Kaffe Fassett talks about his approach to patchwork and quilting, and what makes a good patchwork quilt.",
        "upload_date": "9 months ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "1,968"
      },
      "uploader": {
        "username": "Stitch Craft Create",
        "url": "https://www.youtube.com/user/StitchCraftCreateUK",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Kaffe Fassett Shot Cottons Fabric and Jimmy Beans Wool Fabric Kits Royal Baby Quilt Review",
        "url": "https://www.youtube.com/watch?v=g_dnIhbiYH8",
        "duration": "2:54",
        "snippet": "Gus from Jimmy Beans Wool reviews Kaffe Fassett Shot Cottons Fabric and Jimmy Beans Wool Fabric Kits Royal Baby Quilt.",
        "upload_date": "2 years ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "424"
      },
      "uploader": {
        "username": "Jimmy Beans Wool",
        "url": "https://www.youtube.com/user/JimmyBeansWool",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Mijn Quilt Avontuur!",
        "url": "https://www.youtube.com/watch?v=-JzHGWwZ2bg&list=PLCQrb6JoV_88s8oysgrm3tJthjiJTx4NU",
        "duration": "Playlist",
        "snippet": "View full playlist (31 videos)",
        "upload_date": "1:21",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "Bottom's"
      },
      "uploader": {
        "username": "Mijn Quilt Avontuur!",
        "url": "https://www.youtube.com/channel/UCDSdvOsDjdMp0yintT8snEQ",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Junior 145 - Steffon Fassett (Missouri) vs. Nathan Carmichael (Indiana)",
        "url": "https://www.youtube.com/watch?v=jiBLU3erurw",
        "duration": "3:09",
        "snippet": "Round 2 match of the 2013 USAW Junior Greco Nationals with Steffon Fassett from Missouri vs Nathan Carmichael from Indiana ...",
        "upload_date": "2 years ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "54"
      },
      "uploader": {
        "username": "USA Wrestling",
        "url": "https://www.youtube.com/user/USAWrestling2008",
        "verified": true
      }
    },
    {
      "video": {
        "title": "A Herman Eco Fashion Quilt USA Wool,Org Cotton,vintage",
        "url": "https://www.youtube.com/watch?v=3waJ-KSAeoU",
        "duration": "1:08",
        "snippet": "Eco Designer Anna Herman shows a unique vintage top ,Wool stuffed, American Grown organic coton queen sized Quilt.",
        "upload_date": "4 years ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "412"
      },
      "uploader": {
        "username": "Anna Herman",
        "url": "https://www.youtube.com/user/annafromontana",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Junior 138 - Dylan Herman (Minnesota) vs. Abbas Tamaradze (Massachusetts)",
        "url": "https://www.youtube.com/watch?v=wQMM0kww0K0",
        "duration": "4:20",
        "snippet": "Round 2 match of the 2013 USAW Junior Greco Nationals with Dylan Herman from Minnesota vs Abbas Tamaradze from ...",
        "upload_date": "2 years ago",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "98"
      },
      "uploader": {
        "username": "USA Wrestling",
        "url": "https://www.youtube.com/user/USAWrestling2008",
        "verified": true
      }
    },
    {
      "video": {
        "title": "International Quilt Market & Quilt Shows",
        "url": "https://www.youtube.com/watch?v=FBMWN4kjm2I&list=PLNTabBf7OG9KSwRDOubB0cqx3dUWP2ago",
        "duration": "Playlist",
        "snippet": "View full playlist (126 videos)",
        "upload_date": "25:53",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "All"
      },
      "uploader": {
        "username": "Fat Quarter Shop",
        "url": "https://www.youtube.com/user/FatQuarterShop",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Textile designers",
        "url": "https://www.youtube.com/watch?v=Ash8m16NsrA&list=PLGUBdpm38vhVnGNrUtXt35WvIe17kxyNn",
        "duration": "Playlist",
        "snippet": "View full playlist (21 videos)",
        "upload_date": "4:19",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "Kate"
      },
      "uploader": {
        "username": "yvie212",
        "url": "https://www.youtube.com/user/yvie212",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Ecolo",
        "url": "https://www.youtube.com/watch?v=XupTZRqFFgc&list=PL9GB06795OgoU1MFWba3VWaQ81bDllJXM",
        "duration": "Playlist",
        "snippet": "View full playlist (80 videos)",
        "upload_date": "1:45",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "Pierre"
      },
      "uploader": {
        "username": "Nestaleeman",
        "url": "https://www.youtube.com/user/Nestaleeman",
        "verified": false
      }
    },
    {
      "video": {
        "title": "Popular Patchwork quilt & Patchwork videos",
        "url": "https://www.youtube.com/watch?v=JjSPtYhczCs&list=PLIgUDuU6l5XcGq9jqwZvy_-NO9ct0zNpH",
        "duration": "Playlist",
        "snippet": "View full playlist (200 videos)",
        "upload_date": "16:43",
        "thumbnail_src": "http:https://s.ytimg.com/yts/img/pixel-vfl3z5WfW.gif",
        "views": "quilting"
      },
      "uploader": {
        "username": "#PatchworkQuilt",
        "url": "https://www.youtube.com/channel/UC_NQ6XmmifyR73IMC1n_9sw",
        "verified": false
      }
    }
  ]
}
```
