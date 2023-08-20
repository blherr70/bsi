{% for profile in site.data.profile %}
<ul class="list-unstyled social justify-content-end" id="social-icons">
    {% if profile.linkedin %}
    <li><a href="https://www.linkedin.com/in/{{ profile.linkedin }}/"><i class="bi bi-linkedin secondary--icon secondary--icon-color"></i></a></li>
    {% endif %}
    {% if profile.twitter %}
    <li><a href="https://twitter.com/{{ profile.twitter }}"><i class="bi bi-twitter secondary--icon-color"></i></a></li>
    {% endif %}
    {% if profile.instagram %}
    <li class="mb-2"><a href="{{ profile.instagram }}"><i class="bi bi-instagramsecondary--icon-color"></i></a></li>
    {% endif %}
    {% if profile.youtube %}
    <li class="mb-2"><a href="https://www.youtube.com/@{{ profile.youtube }}"><i class="bi bi-youtube secondary--icon-color"></i></a></li>
    {% endif %}
    {% if profile.pinterest %}
    <li class="mb-2"><a href="https://www.pinterest.com/{{ profile.pinterest }}/"><i class="bi bi-pinterest secondary--icon-color"></i></a></li>
    {% endif %}

</ul>

{% endfor %}  