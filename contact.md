---
title: contact
---

<section>
	<h3 class="major"></h3>
	<p>Email: thomas.hudson@earth.ox.ac.uk</p>
	<p><a href="https://www.earth.ox.ac.uk/people/thomas-hudson/">Department webpage</a><br></p>
	<p>Deapartment of Earth Sciences<br>University of Oxford<br>3 South Parks Rd<br>Oxford<br>OX1 3AN<br>United Kingdom </p>

	<h3 class="major">Email me</h3>
	<form method="post" action="#">
        <div class="fields">
            <div class="field half first">
                <label for="demo-name">Name</label>
                <input type="text" name="demo-name" id="demo-name" value="" placeholder="Your Name" />
            </div>
            <div class="field half">
                <label for="demo-email">Email</label>
                <input type="email" name="demo-email" id="demo-email" value="" placeholder="your_email@blah.com" />
            </div>
            <div class="field">
                <label for="demo-category">Category</label>
                <div class="select-wrapper">
                    <select name="demo-category" id="demo-category">
                        <option value="">-</option>
                        <option value="1">Research collaboration</option>
                        <option value="1">Press enquiry</option>
                        <option value="1">Outreach</option>
                        <option value="1">Other</option>
                    </select>
                </div>
            </div>
            <div class="field half first">
                <input type="radio" id="demo-priority-low" name="demo-priority" checked>
                <label for="demo-priority-low">Low</label>
            </div>
            <div class="field half">
                <input type="radio" id="demo-priority-high" name="demo-priority">
                <label for="demo-priority-high">High</label>
            </div>
            <div class="field half first">
                <input type="checkbox" id="demo-copy" name="demo-copy">
                <label for="demo-copy">Email me a copy</label>
            </div>
            <div class="field half">
                <input type="checkbox" id="demo-human" name="demo-human" checked>
                <label for="demo-human">Not a robot</label>
            </div>
            <div class="field">
                <label for="demo-message">Message</label>
                <textarea name="demo-message" id="demo-message" placeholder="Enter your message" rows="6"></textarea>
            </div>
        </div>
		<ul class="actions">
			<li><input type="submit" value="Send Message" class="special" /></li>
			<li><input type="reset" value="Reset" /></li>
		</ul>
	</form>

</section>



<ul class="icons">

	{% if site.twitter_url %}
				<li><a href="{{ site.twitter_url }}" class="icon fa-twitter" target="_blank"><span class="label">Twitter</span></a></li>
				{% endif %}
				{% if site.googleplus_url %}
				<li><a href="{{ site.googleplus_url }}" class="icon fa-google-plus" target="_blank"><span class="label">Google+</span></a></li>
				{% endif %}
				{% if site.facebook_url %}
				<li><a href="{{ site.facebook_url }}" class="icon fa-facebook" target="_blank"><span class="label">Facebook</span></a></li>
				{% endif %}
				{% if site.instagram_url %}
				<li><a href="{{ site.instagram_url }}" class="icon fa-instagram" target="_blank"><span class="label">Instagram</span></a></li>
				{% endif %}
				{% if site.pinterest_url %}
				<li><a href="{{ site.pinterest_url }}" class="icon fa-pinterest" target="_blank"><span class="label">Pinterest</span></a></li>
				{% endif %}
				{% if site.gitlab_url %}
				<li><a href="{{ site.gitlab_url }}" class="icon fa-gitlab" target="_blank"><span class="label">GitLab</span></a></li>
				{% endif %}
				{% if site.github_url %}
				<li><a href="{{ site.github_url }}" class="icon fa-github" target="_blank"><span class="label">GitHub</span></a></li>
				{% endif %}
				{% if site.slack_url %}
				<li><a href="{{ site.slack_url }}" class="icon fa-slack" target="_blank"><span class="label">Slack</span></a></li>
				{% endif %}
				{% if site.linkedin_url %}
				<li><a href="{{ site.linkedin_url }}" class="icon fa-linkedin" target="_blank"><span class="label">LinkedIn</span></a></li>
				{% endif %}

</ul>
