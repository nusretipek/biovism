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
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
	width: 1500px;
	align-items: center;
	align-content: center;
	justify-content: center;
	place-items: center;
	grid-gap: 30px;
}

.title {
   margin: 20px 0;
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
.content p {margin: 0;}

h3 {
  font-size: 20px;
}

body {
	margin-top: 50px;
}

p {
  font-size: 16px;
}

.site-footer {
	position: absolute; 
	margin-top: -45px;
	left: 50%;
	transform: translateX(-50%); 
}


</style>

<div class="title"><h2><strong>Prospective Students</strong></h2></div>
<div class='students'>
	<div class='phd'>
		<div class="title">
			<h3><strong>PhD students</strong></h3>
		</div>
		<div class="content">
			<img src="phd.png" style="height: 100px; width:100px;">
			<div class="text">
				<p>Check current vacancies from <a href="https://www.ugent.be/en/work/scientific">UGent Doctoral fellows</a> </p>
			</div>
		</div>
	</div>
	<div class='graduate'>
		<div class="title">
			<h3><strong>Masters | Undergraduates | Visitors</strong></h3>
		</div>
		<div class="content">
			<img src="grad.png" style="height: 100px; width:100px;">
			<div class="text">
				<p>Thank you for your interest in participating in our research. <br> For application as a researcher, please send us your CV and motivation letter. </p>
			</div>
		</div>
	</div>
</div>


<!-- Contact Information -->

<div class="titleContact"><h2><strong>Contact Information</strong></h2></div>

<div class="contact">
	<div><img src="address.png" style="height: 100px; width:100px;"></div>
	<div><img src="phone.png" style="height: 100px; width:100px;"></div>
	<div><img src="email.png" style="height: 100px; width:100px;"></div>
	<div><a href="https://goo.gl/maps/i8HWBFsRyHHMwRN4A">Campus Coupure, Block A 1st floor 110.079, Coupure links 653, B-9000 Ghent, Belgium</a></div>
	<div><a href="tel:+32 9 264 59 33">+32 9 264 59 33</a> </div>
	<div><a href="mailto:Jan.Verwaeren@UGent.edu">Jan.Verwaeren@UGent.edu</a></div>
</div>
