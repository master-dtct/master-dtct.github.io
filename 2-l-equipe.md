---
layout: page
title: L'équipe enseignante
---

L'équipe se compose d'enseignants titulaires à l'Université Toulouse Jean Jaurès et de professionnels du design, du marketing...
Cette page est en cours de réalisation.

<div class="flex-container">
	{% for person in site.data.staff %}
	<div class="flex-item">
		{% if person.photo %}
		<img src="/../img/profiles/teachers/ID-{{ person.photo }}" class="flex-image"/>
		{% else %}
		<div class="flex-image"></div>
		{% endif %}
		<p class="flex-personne-name">{{ person.name }}</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">{{ person.quality }}</p>
			{% for detail in person.details %}
				<p class="flex-personne-details">
					{{ detail | markdownify | remove: '<p>' | remove: '</p>' }}
				</p>
			{% endfor %}
		</div>
	</div>
	{% endfor %}

		<div class="flex-item">
		<img src="/../img/profiles/teachers/ID-cazin.jpg" class="flex-image"/>
		<p class="flex-personne-name">Émilie Cazin</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Designer</p>
			<p class="flex-personne-details"><a href="http://emiliecazin.com/" target="_blank">Site personnel</a></p>
			<p class="flex-personne-details"><a href="https://www.facebook.com/EmilieCazinDesign/?view_public_for=170576826291466" target="_blank">Sur Facebook</a></p>
		</div>
	</div>

	<div class="flex-item">
		<img src="/../img/profiles/teachers/ID-denoual.jpg" class="flex-image"/>
		<p class="flex-personne-name">Fabienne Denoual</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Maître de Conférences en Design</p>
			<p class="flex-personne-details"><a href="https://www.linkedin.com/in/fabienne-denoual-33464b58" target="_blank">Sur LinkedIn</a></p>
		</div>
	</div>

			<div class="flex-item">
		<div class="flex-image"></div>
		<!--<img src="#" class="flex-image"/>-->
		<p class="flex-personne-name">Thierry Dubrouil</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Chargé de cours</p>
		</div>
			</div>

		<div class="flex-item">
		<div class="flex-image"></div>
		<!--<img src="#" class="flex-image"/>-->
		<p class="flex-personne-name">Brice Genre</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Enseignant-Chercheur et Designer</p>
			<p class="flex-personne-details"><a href="http://www.aplusbdesigners.com/" target="_blank">a + b designers</a></p>
		</div>
		</div>

	<div class="flex-item">
		<img src="/../img/profiles/teachers/ID-guillaumot.jpg" class="flex-image"/>
		<p class="flex-personne-name">Thomas Guillaumot</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Design & Stories</p>
			<p class="flex-personne-details"><a href="https://fr.linkedin.com/in/thomasguillaumot" target="_blank">Sur LinkedIn</a></p>
			<p class="flex-personne-details"><a href="http://ekito.fr" target="_blank">ekito</a> / <a href="http://zombicat.net" target="_blank">zombicat</a> / <a href="http://garlicdesign.com" target="_blank">garlicdesign</a></p>
		</div>
	</div>

	<div class="flex-item">
		<img src="/../img/profiles/teachers/ID-guizard.jpg" class="flex-image"/>
		<p class="flex-personne-name">Damien Guizard</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Architecte, Designer, Maquettiste</p>
			<p class="flex-personne-details"><a href="http://guizard.net" target="_blank">guizard.net</a></p>

		</div>
	</div>

		<div class="flex-item">
		<img src="/../img/profiles/teachers/ID-masure.jpg" class="flex-image"/>
		<p class="flex-personne-name">Anthony Masure</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Enseignant-Chercheur, Designer d’interfaces</p>
			<p class="flex-personne-details"><a href="http://www.anthonymasure.com/" target="_blank">anthonymasure.com</a></p>
			<p class="flex-personne-details"><a href="https://twitter.com/anthonymasure?lang=en" target="_blank">Sur Twitter</a></p>
		</div>
	</div>

		<div class="flex-item">
		<div class="flex-image"></div>
		<!--<img src="#" class="flex-image"/>-->
		<p class="flex-personne-name">Bianca Millon-Devigne</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Graphiste</p>
		</div>
		</div>

<!--
		<div class="flex-item">
		<img src="/../img/profiles/teachers/james-doe.jpg" class="flex-image"/>
		<p class="flex-personne-name" style="font-size: 1em;">John Superlonglastname</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Designer, Enseignant-Chercheur</p>
			<p class="flex-personne-details"><a href="#" target="_blank">@johnsuperlonglastname</a></p>
			<p class="flex-personne-details"><a href="#" target="_blank">www.johnsuperlonglastname.com</a></p>
		</div>

	</div>

		<div class="flex-item">
		<img src="/../img/profiles/teachers/jenny-social.jpg" class="flex-image"/>
		<p class="flex-personne-name" style="font-size: 1em;">Jenny Socialmedia</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Designer, Enseignant-Chercheur</p>
			<p class="flex-personne-details"><a href="#" target="_blank">@jennysocial</a></p>
			<p class="flex-personne-details"><a href="#" target="_blank">www.jennysocial.com</a></p>
		</div>

	</div>

		<div class="flex-item">
		<img src="/../img/profiles/teachers/julie-doe.jpg" class="flex-image"/>
		<p class="flex-personne-name">Julie Doe</p>
		<div class="flex-personne-detailbox">
			<p class="flex-personne-quality">Sociologue, Philosophe, Enseignante-Chercheuse</p>
			<p class="flex-personne-details"><a href="#" target="_blank">@juliedoe</a></p>
			<p class="flex-personne-details"><a href="#" target="_blank">www.juliedoe.com</a></p>
		</div>

	</div>
-->

</div>
