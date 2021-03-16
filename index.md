---
layout: page
---

The Herschel Extragalactic Legacy Project (HELP) provides techniques, tools and data to enable astronomers in Europe and globally to capitalise on the surveys of the distant Universe made by the ESA mission Herschel. HELP can also be very useful for providing overviews of optical to near infrared public surveys that are available on a given extragalactic field. Users often wish to find out what data is available on a given field. As a first step it can be instance to look at the overview of a field such as the [ELAIS-N1](http://hedam.lam.fr/HELP/dataproducts/dmu31/dmu31_Field_overviews/ELAIS-N1.html) field. You can see a set of links to every field overview [here](http://hedam.lam.fr/HELP/dataproducts/dmu31/dmu31_Field_overviews/).

The [data access](http://herschel.sussex.ac.uk/data_access/) page contains information about how to access and use all the data and tools. For some people they might wish to get the [SPIRE imaging on every field](http://hedam.lam.fr/HELP/dataproducts/dmu19/dmu19_HELP-SPIRE-maps/data/). For others they might want the final merged catalogue on a given field such as [ELAIS-N1](http://hedam.lam.fr/HELP/dataproducts/dmu32/dmu32_ELAIS-N1/data/). Others might want to use a query to get an all sky sample of objects with a [photometric redshift above 4](https://herschel-vos.phys.sussex.ac.uk/__system__/adql/query/form?__nevow_form__=genForm&query=SELECT%20TOP%2010%20*%20from%20help_a_list.main%20WHERE%20redshift%20%3E%204&_TIMEOUT=5&_FORMAT=HTML&submit=Go). These are just some examples. HELP contains a wealth of data sets and we hope that this site will help you find useful data to further your science goals.

![EU flag]({{site-url}}/assets/images/flag_yellow_low.jpg?w=300&h=200)

This project has received funding from the European Union’s Seventh Framework
Programme for research, technological development and demonstration under grant
agreement no 607254.



<div class="home">

  <h1 class="page-heading">Events</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>


</div>
