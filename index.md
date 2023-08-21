  ```bio-meta
{
    "name": "Zongyuan Liu",
    "title": "Zongyuan Liu",
    "description": "Zongyuan Liu&#8217;s curriculum vitae.",
    "url": "https://cs.au.dk/~zyliu/",
    "assets": "https://cs.au.dk/~zyliu/assets",
    "date-created": "2022-08-18",
    "repo": "https://github.com/lzy0505/bio-site",
    "tilecolor": "#f2f2f2"
}
```

# Zongyuan Liu

<figure class="gl-page-background gl-float-right gl-image-box" style="text-align: center;"><img src="assets/images/self.jpg" alt="A photo of Zongyuan Liu" width="160" height="160" style="max-width: 160px;" /></figure>

I’m a third-year Ph.D. student in computer science at Aarhus University, advised by [Lars Birkedal](https://cs.au.dk/~birke/). I am interested in program verification.

<!-- Prior to joining [unknown current university](https://example.com/), I obtained my bachelor’s degree from [unknown previous university](https://example.com/). -->

I can be reached at <span id="_eml" class="gl-eml">zy dot liu at cs dot au dot dk</span>.

```bio-remove
Below we use a simple mechanism to mitigate email address reaping.
Change the encoding for your own email address.
```

<!--[bio][protect]
<script type="application/javascript">
window.setTimeout(function ()
{
var addr = [122,121,46,108,105,117,64,99,115,46,97,117,46,100,107];
addr = String.fromCharCode.apply(String, addr);
var eml = document.getElementById('_eml');
eml.innerHTML = '<a href="mailto:' + addr + '">' + addr + '</a>';
eml.removeAttribute('class');
}, 600);
</script>
[bio]-->

<!-- This is an example personal homepage built with [bio-site](https://github.com/GeeLaw/bio-site). It features simplicity and integration with BibTeX. -->


## Publications

```blog-bib

@comment
{
Use #bibitem_Venue_Key to refer to "Venue:Key".

It is possible to have multiple BibTeX blocks, which will be rendered independently. For example, you might want to have one block for each of "Publications", "Pre-prints", and "Manuscripts".

To support more information links (e.g., add "slides" or "pdf" links),
see "builder/marked.0.3.6/bibtex-service.js" line 109.
}

@online{Liu:Hypveri,
  author = {Zongyuan Liu and Sergei Stepanenko and Jean Pichon-Pharabod and Amin Timany and Aslan Askarov and Lars Birkedal},
  title = {VMSL: A Separation Logic for Mechanised Robust Safety of Virtual Machines Communicating above FF-A},

  biosite_venue = {PLDI 23},
  biosite_preprint = {assets/papers/hypveri.pdf},

}

```


## Talks

```blog-bib
@misc{iris-workshop,
  biosite_venue = {Iris Workshop 2022},
  title = {A Separation Logic for Communicating Virtual Machines},
  author = {Zongyuan Liu and Sergei Stepanenko and Jean Pichon-Pharabod and Amin Timany and Aslan Askarov and Lars Birkedal},
  
  biosite_slides = {assets/papers/iris-workshop.pdf},
}
```
