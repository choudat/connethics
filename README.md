
{% include header.html %}

## Contact me
Contact me directly on [LinkedIn] via direct message or WhatsApp if you have my mobile.

Fresh & new: You can also ask for quote from my [Malt] account.

[LinkedIn]: https://www.linkedin.com/in/fredericchoudat/
[malt]: https://malt.fr/profile/fredericchoudat

## Subscribe! 
If you want to keep in touch without specific topics, be pleased to subscribe to my non regular newsletter. I'm using this mailing list to share some taught and my actuality. If you have thoughts or feedback, please let me know. All replies to my monthly emails go directly to me.
{% include mailchimp.html %} 

## Why ConnEthics ?

[ConnEthics] want to support sustainable activities which are playing in a deeply interconnected ecosystem:
* Take advantage of your position within the value chain
* Build new revenue stream from your partners
* Define a feature and communication roadmap to support complex growth when dealing with multiface business model
* Enlarge the Customer centric approach to the partner as chrun on partner could have massive impact 
* Set a corporate mindset to run a virtuous circle supporting partners and customers growth

[connethics]: http://connethics.fr

# a short blog ?
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

{% include footer.html %}

