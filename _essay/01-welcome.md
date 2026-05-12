---
title: Feels Like Power: Immersive VR Poetry
order: 1
part: Overview and Examples
---

Feels Like Power is a collection of immersive VR poems about the long afterlives of the Pacific War.

The project’s poems are set primarily in and around U.S. military bases in Japan, Korea, Guam, Singapore, and the Philippines, but also include locations in the U.S. and in cyberspace.

The poems are written inside panoramic spherical photographs. When you read the poems in 3D, the poems extend panoramically around, above, and below you. By moving your head and body, you can navigate the environment and the text within it. This website enables VR within each poem for those who have VR headsets, but also features 2D versions which are accessible simply with a phone, tablet, or laptop. 

The project invites you to experience poems spatially in each site, and to travel between sites to discover resonances and contrasts. What can we learn about war, about its overlap with domestic life, about history and humanity, from bringing these distinct places with their distinct histories into contact with each other?



## So What Is It?

***CB-Essay*** is a Jekyll-based framework that combines **long-form essay writing** with **digital collection features**. Built on [CollectionBuilder](https://collectionbuilder.github.io/), it enables you to create multimodal scholarly narratives, written in Markdown, that integrate primary sources, archival materials, and multimedia items directly into your texts.

Traditional digital publishing tools treat essays and collections as separate entities. CB-Essay connects them, allowing you to:

- **Reference collection items** using simple includes
- Create **asides and margin notes** that link to primary sources {% include /essay/feature/aside.html text="Like this!" %}
- **Publish your work for free** on GitHub
- Generate **well-designed print and pdf outputs** using PagedJS.
- **Choose from 8 accessible color themes** or create your own custom palette
- Fashion the readers' experience through **scroll-based interactions and coordinated typography** {% include /essay/feature/aside.html text="Keep scrolling to see the next section magically appear!" %}

{% include essay/new-section.html %}

## How Does It Work?

CB-Essay operates on a **dual-collection model**:

1. **Essay Collection** - Your narrative content lives in the `_essay/` folder as Markdown files
2. **Object Collection** - Primary sources and items defined in a CSV metadata file

The dual collection model lets you write ***with*** your collection of sources, allowing you to integrate references, images, documents, recordings, and videos seamlessly into your writing and into the web. 

Just follow the plan, as detailed in the below image.{% include essay/feature/aside.html text="Below image credits: The Miriam and Ira D. Wallach Division of Art, Prints and Photographs: Photography Collection, The New York Public Library. 'Group farm plan writing meeting. Weld County, Colorado' The New York Public Library Digital Collections. [https://digitalcollections.nypl.org/items/1b0a3fc0-1d42-0139-bac7-0242ac110003](https://digitalcollections.nypl.org/items/1b0a3fc0-1d42-0139-bac7-0242ac110003)" %}

{% include feature/image.html objectid="/assets/img/writing-plan.jpg" caption="The tool is no more complicated than following this gentleman's instructions!" alt="Group working on a farm plan writing project with man pointing at a complex plan written on a large sheet of paper at the front"%}




## Who Should Use CB-Essay?

- **Digital humanists** creating annotated editions or critical apparatus
- **Historians** presenting narrative alongside primary sources
- **Educators** building interactive course readers
- **Archivists** creating context around collections
- **Writers** publishing long-form digital scholarship
- **Students** looking to improve their knowledge of web and print design


### Bonus: Project Gutenberg Extractor

Want to publish a public domain book? Use our [**GitHub Action**](https://dcnb.github.io/frankenstein/action.mp4) to extract any of **60,000+ books** from Project Gutenberg directly into your `_essay/` folder - pre-formatted for the site. 


## Next Steps

Check out some examples sites, then get started. The remaining essays show off CB-Essay in the wild, and then walk you through setting up your first site and understanding the features.

- **[See Examples](02-examples.html)** - See CB-Essay as used for DH projects and in demonstration 
- **[Get Started](03-get-started.html)** - Set up your first essay in 10 minutes
- **[Essay Features](04-essay-features.html)** - Learn and copy all available features
- **[Collection Integration](05-collection-integration.html)** - Blend essays with collection items

Or jump straight to the [documentation]({{ '/docs.html' | relative_url }}) for reference guides.

---


