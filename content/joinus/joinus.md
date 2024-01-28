---
widget: blank
headless: false

# ... Put Your Section Options Here (title etc.) ...
title: 
subtitle:
weight: 10  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
---

<style>
  .content {
    display: flex;
    align-items: center;
  }

  .contact {
    display: grid;
    grid-auto-flow: row;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    max-width: 700px; /* Instead of setting a fixed width, use max-width */
    margin: 0 auto; /* Center the grid horizontally */
    align-items: center;
    align-content: center;
    justify-content: center;
    place-items: center;
    grid-gap: -10px;
	font-size: 16px;
  }

  .title {
    margin: 20px 0;
  }
  
  .contact iframe {
	grid-column: span 1; /* Make the iframe span all three columns */
  }
  .titleContact {
    margin-top: 50px;
    margin-bottom: 25px;
  }

  .content img {
    margin-right: 10px;
    display: block;
  }

  .content h3,
  .content p {
    margin: 0;
  }

  h3 {
    font-size: 20px;
  }

  body {
    margin-top: 50px;
    margin-bottom: 50px; /* Adjust the bottom margin to create space for the footer */
  }

  p {
    font-size: 16px;
    text-align: justify;
  }

  .site-footer {
    text-align: center; /* Center the text in the footer */
  }
</style>

<html>
<div class="title"><h2><strong>Prospective Students</strong></h2></div>
<div class='students'>
	<div class='phd'>
		<div class="title">
			<h3><strong>PhD students</strong></h3>
		</div>
		<div class="content">
			<img src="phd.png" style="height: 100px; width:100px;">
			<div class="text">
				<p> Interested in joining the team as a PhD student? Check the following vacancies: </p>
				 <ul>
				   <li><p>There are no currently open positions </p></li>
				   <li><p>Interested in a PhD position that focuses on the mathematical aspects of computer vision, feel free to send a letter of motivation, CV and a recent publication (such as your master thesis) to <a href = "mailto: jan.verwaeren@ugent.be">jan.verwaeren@ugent.be</a> </p> </li>
				 </ul> 
			    </p>
			</div>
		</div>
	</div>
	<div class='graduate'>
		<div class="title">
			<h3><strong>Bachelor | Master students </strong></h3>
		</div>
		<div class="content">
			<img src="grad.png" style="height: 100px; width:100px;">
			<div class="text">
				<p>Thank you for your interest in participating in our research. Master and bachelor thesis topics can be found at <a href="https://www.ugent.be/bw/nl/voor-studenten#Curriculumsamenstellen"> here </a> </p>
			</div>
		</div>
	</div>
</div>


<!-- Contact Information -->

<div class="titleContact"><h2><strong>Contact Information</strong></h2></div>
  <div>
    <iframe
      width="100%"
      height="350"
      frameborder="0"
      style="border: 0"
      src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d10032.062020593983!2d3.7089!3d51.0528015!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c3716c05a9b1bd%3A0xe9c273e321db3dd9!2sUniversiteit%20Gent%20-%20Campus%20Coupure!5e0!3m2!1str!2sbe!4v1706356098587!5m2!1str!2sbe"
      allowfullscreen
    ></iframe>
  </div>
  </br>
<div class="contact">

  <div><img src="phone.png" style="height: 72px; width:72px;"></div>
  <div><img src="email.png" style="height: 72px; width:72px;"></div>
  <div><a href="tel:+32 9 264 59 33">+32 9 264 59 33</a></div>
  <div><a href="mailto:Jan.Verwaeren@UGent.be">Jan.Verwaeren@UGent.be</a></div>
</div>
</html>