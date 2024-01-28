---
widget: blank
headless: false

# ... Put Your Section Options Here (title etc.) ...
title: 
subtitle:
weight: 10 
design:
  columns: '1'
---

 <!-- STYLE CSS -->

<style>
  .content {
    display: flex;
    align-items: center;
  }

  .title {
    margin: 20px 0;
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
    margin-bottom: 50px
  }

  p {
    font-size: 16px;
    text-align: justify;
  }

  .site-footer {
    text-align: center; /* Center the text in the footer */
  }

	.news {
		font-size:14px;
		margin-bottom: 13px;
	}

	.expandable-section {
			max-height: 0;
			overflow: hidden;
			transition: max-height 0.3s ease-out;
	}

	.expandable-section.active {
			max-height: 2000px; /* Adjust the maximum height as needed */
			max-width: 1000px; /* Adjust the maximum height as needed */

	}

	.arrow {
			margin-left: 10px;
			display: inline-block;
			width: 0;
			height: 0;
			border-style: solid;
			border-width: 8px 0 8px 16px;
			border-color: transparent transparent transparent #000 ;
			transition: transform 0.3s ease-out;
	}
	
	.arrow-container.active .arrow {
			border-color: transparent transparent transparent forestgreen; /* Change color to light green when active */
	}
	
	.arrow.down {
			transform: rotate(90deg);
	}
	
	.expandable-header {
			cursor: pointer;
	}
	
	.arrow-container {
			display: flex;
			align-items: center;
	}

</style>


<html>
<div class="title"><h2><strong>Biweekly News</strong></h2></div>

<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 1 | 10 Jan 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<ol>
  <li class="news"><p>Last year was the breakthrough year for Large Language Models (LLMs), check out the round up the highlights in one blogpost. <br>
  <a href="https://simonwillison.net/2023/Dec/31/ai-in-2023/" target="_blank">Simon Willison’s Weblog</a> </p></li>
  <li class="news"><p> To showcase evolution of AI in 2023, check out the a visual timeline, highlighting the most remarkable AI advancements that have shaped this year of AI. <br>
  <a href="https://journal.everypixel.com/2023-the-year-of-ai" target="_blank">Everypixel Journal</a> </p></li>
  <li class="news"><p>Using AI, MIT researchers identify a new class of antibiotic candidates. These compounds can kill methicillin-resistant Staphylococcus aureus (MRSA), a bacterium that causes deadly infections. <br>
  <a href="https://news.mit.edu/2023/using-ai-mit-researchers-identify-antibiotic-candidates-1220" target="_blank">MIT News</a> </p></li>
  <li class="news"><p>New research shows that even subtle changes to digital images, designed to confuse computer vision systems, can also affect human perception. <br>
  <a href="https://deepmind.google/discover/blog/images-altered-to-trick-machine-vision-can-influence-humans-too/" target="_blank">Google: DeepMind</a> </p></li>
  <li class="news"><p>Microsoft Phi-2 transformer model becomes open source (MIT Licence). Phi-2 model is a 2.7 billion-parameter language model that demonstrates outstanding reasoning 
  and language understanding capabilities, showcasing state-of-the-art performance among base language models with less than 13 billion parameters. <br>
  <a href="https://huggingface.co/microsoft/phi-2" target="_blank">Huggingface: Phi-2</a> </p></li>
  <li class="news"><p>Apple enters the game with ml-ferret and open source a new multimodal large language model (MLLM), 
  capable of understanding spatial referring of any shape or granularity within an image and accurately grounding open-vocabulary descriptions. 
  In English, Mac users soon command, for example zoom to the X object in the Y side of the screen. <br>
  <a href="https://github.com/apple/ml-ferret/" target="_blank">GitHub: ml-ferret</a> </p></li>
  <li class="news"><p> Are you a heavy user of Python Pandas library, and things get slow after a million rows? Check out the RAPIDS cuDF for upto 150x performance improvement. <br>
  <a href="https://www.youtube.com/watch?v=Yl3xCV2bN6E" target="_blank">YouTube: Tech With Tim</a> </p></li>
  <li class="news"><p> Homomorphic encryption is a form of encryption that allows computations to be performed on encrypted data without first having to decrypt it.
  Although, it was software-level so far, chips to compute with encrypted data is on the way for fully homomorphic encryption (unhackable data!?). <br>
  <a href="https://spectrum.ieee.org/homomorphic-encryption" target="_blank">IEEE: Spectrum</a> </p></li>
  <li class="news"><p> OpenAI will open its custom ChatGPT store next week. The store to share and sell custom AI agents will launch after being delayed for a month. <br>
  <a href="https://www.theverge.com/2024/1/4/24025610/openai-gpt-store-ai-agent-delay" target="_blank">The Verge</a> </p></li>  
  <li class="news"><p> New meta-analysis: On average, undergraduate students' intelligence is merely average. 
  The results show that the average IQ of undergraduate students today is a mere 102 IQ points and declined by approximately 0.2 IQ points per year. <br>
  <a href="https://www.frontiersin.org/articles/10.3389/fpsyg.2024.1309142/abstract" target="_blank">Frontiers in Psychology</a> </p></li>    
  <li class="news"><p> Searching the Internet for information sucks, and things getting worse. How bad are search results? Let's compare Google, Bing, Marginalia, <strong>Kagi (recent favorite engine of tech community)</strong>, Mwmbl, and ChatGPT. <br>
  <a href="https://danluu.com/seo-spam/" target="_blank">Danluu blog</a> </p></li>      
  <li class="news"><p> The most popular programming languages since 1965 to 2022 (video). <br>
  <a href="https://twitter.com/Rainmaker1973/status/1741077744622907545" target="_blank">X (old Twitter)</a> </p></li>   
  <li class="news"><p>The Splatter Image is an ultra-fast method for single- and few-view 3D reconstruction. It can be trained using only 1 GPU, with reconstruction is done at 38 FPS. <br>
  <a href="https://szymanowiczs.github.io/splatter-image" target="_blank">GitHub: Splatter Image</a> </p></li>
  <li class="news"><p>More and more unified frameworks are coming to the field, one interesting example is GLEE. 
  It is an object-level foundation model for locating and identifying objects in images and videos. 
  Through a unified framework, GLEE accomplishes detection, segmentation, tracking, grounding, and identification of arbitrary objects in the open world scenario for various object perception tasks. <br>
  <a href="https://glee-vision.github.io" target="_blank">GitHub: GLEE</a> </p></li>
  <li class="news"><p> Following EfficientSAM, another improvement on the segment anything model (SAM). TinySAM: Pushing the Envelope for Efficient Segment Anything Model. <br>
  <a href="https://arxiv.org/abs/2312.13789" target="_blank">arXiv: Computer Vision and Pattern Recognition</a> </p></li>
  <li class="news"><p><strong>Fun project: </strong> Suprised by the outcomes of a Python snippet; check out this fun project attempting to explain what exactly is happening under the hood 
  for some counter-intuitive snippets and lesser-known features in Python. <br> 
  <a href="https://github.com/satwikkansal/wtfpython" target="_blank">GitHub: wtfpython</a> </p></li>
</ol>
</div>

<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 2 | 24 Jan 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<ol>
	<li class="news"><p> Fingerprint biometrics are integral to digital authentication and forensic science. However, they are based on the unproven assumption that no two fingerprints, 
	even from different fingers of the same person, are alike. Contrary to this prevailing assumption, this study shows above 99.99% confidence that fingerprints from different fingers of the same 
	person share very strong similarities.<br>
	<a href="https://www.science.org/doi/10.1126/sciadv.adi0329" target="_blank">Science Advances</a></p></li>
	<li class="news"><p>PEDS: a new technique could efficiently solve partial differential equations for numerous applications.  <br>
	<a href="https://news.mit.edu/2024/peds-technique-could-efficiently-solve-partial-differential-equations-0108" target="_blank">MIT News</a></p></li>  
	<li class="news"><p>New EU project NGI TALER will bring private and secure online payments to the Eurozone. An innovative electronic payment system for the greater benefit of European citizens, merchants, and banks. 
	This payment system is different from current online payment methods, like credit cards or bank transfers, in that it offers privacy for the buyer: neither merchants nor banks can trace or link the payments.<br>
	<a href="https://taler.net/en/news/2024-02.html" target="_blank">TALER</a></p></li>
	<li class="news"><p>AlphaGeometry: An Olympiad-level AI system for geometry. An AI system that surpasses the state-of-the-art approach for geometry problems, advancing AI reasoning in mathematics by Google DeepMind.<br>
	<a href="https://deepmind.google/discover/blog/alphageometry-an-olympiad-level-ai-system-for-geometry/" target="_blank">Google: DeepMind</a> </p></li>
	<li class="news"><p>Researchers Claim First Functioning Graphene-Based Chip. The semiconductor bests silicon alternatives for electron mobility. 
	The silicon as a semiconducter reaching its limits (<a href="https://en.wikipedia.org/wiki/Moore%27s_law" target="_blank">Moore's law</a> is dead?), the graphene-based chip (graphene is not semiconductor as material) 
	has huge potential. <br>
	<a href="https://spectrum.ieee.org/graphene-semiconductor" target="_blank">IEEE Spectrum</a> & <a href="https://www.youtube.com/watch?v=oXBtPmVrES4&t=2s" target="_blank">YouTube: Science News</a> </p></li>	
	<li class="news"><p>Researchers think their AI system could help to democratize medicine. Google AI has better bedside manner than human doctors — and makes better diagnoses. <br>
	<a href="https://www.nature.com/articles/d41586-024-00099-4" target="_blank">Nature</a></p></li> 	
	<li class="news"><p>Cloned rhesus monkey lives to adulthood for the first time. A method that provides cloned embryos with a healthy placenta could pave the way for more research involving primates. <br>
	<a href="https://www.nature.com/articles/d41586-024-00136-2" target="_blank">Nature</a></p></li>	
	<li class="news"><p>Bill Gates's opinion on 2024; lifesaving chatbots, 2024 election, malnutrition breakthrough, AI-powered innovation, climate conversation and more.<br>
	<a href="https://www.gatesnotes.com/The-Year-Ahead-2024" target="_blank">The Blog of Bill Gates</a></p></li>
	<li class="news"><p> Microsoft Adds AI Key in First Change to PC Keyboard in Decades. The new Copilot button is the first addition since the Windows key in 1994.<br>
	<a href="https://www.bloomberg.com/news/articles/2024-01-04/microsoft-ai-copilot-keyboard-new-key-is-msft-s-biggest-change-in-years" target="_blank">Bloomberg Technology</a></p></li>
	<li class="news"><p>The World's first-ever smart binoculars can identify 9,000 birds thanks to built-in AI. <br>
	<a href="https://www.digitalcameraworld.com/news/worlds-first-ever-smart-binoculars-can-identify-up-to-9000-birds-thanks-built-in-ai" target="_blank">Digital Camera World</a></p></li> 	
	<li class="news"><p>Version 14 of Wolfram Language and Mathematica brings new functions and updates. <br>
	<a href="https://writings.stephenwolfram.com/2024/01/the-story-continues-announcing-version-14-of-wolfram-language-and-mathematica/" target="_blank">Stephen Wolfram: Writings</a></p></li>	
	<li class="news"><p>Marimo: a recent attempt on reactive Python notebooks. . It allows you to rapidly experiment with data and models, 
	code with confidence in your notebook's correctness, and productionize notebooks as pipelines or interactive web apps. <br>
	<a href="https://github.com/marimo-team/marimo" target="_blank">GitHub: marimo</a></p></li>
	<li class="news"><p> As the large multi-modal networks arise and they are hungry for data, the protection of the intellectual property becomes shady. A new attempt to help artists prevent their content 
	fed into generative AI models is Nightshade. It is a tool that turns any image into a data sample that is unsuitable for model training. More precisely, Nightshade transforms images into "poison" samples, 
	so that models training on them without consent will see their models learn unpredictable behaviors that deviate from expected norms. <br>
	<a href="https://nightshade.cs.uchicago.edu/index.html" target="_blank">Sand Lab, University of Chicago</a></p></li>	
	<li class="news"><p>From Meta AI, a new approach to enhancing the language models; Self-Rewarding Language Models. The language model itself is used via LLM-as-a-Judge prompting to provide 
	its own rewards during training. Although preliminary research, it already outperforms many existing systems on the AlpacaEval 2.0 leaderboard, including Claude 2, Gemini Pro, and GPT-4. <br>
	<a href="https://arxiv.org/abs/2401.10020" target="_blank">arXiv: Self-Rewarding Language Models</a></p></li>
	<li class="news"><p>Mark Zuckerberg’s new goal is to create artificial general intelligence with 600,000 GPUs by the end of 2024.<br>
	<a href="https://www.theverge.com/2024/1/18/24042354/mark-zuckerberg-meta-agi-reorg-interview" target="_blank">The Verge</a> </p></li>
	<li class="news"><p>For Android users: Google is making changes to Google Assistant by removing some underutilized features in Google Assistant to focus on delivering the best possible user experience.<br>
	<a href="https://blog.google/products/assistant/google-assistant-update-january-2024/" target="_blank">Google: Products</a></p></li>
	<li class="news"><p> After the boom in AI, robotics appears to be booming in the following year. Toyota's Robots Are Learning to Do Housework—By Copying Humans. <br>
	<a href="https://archive.ph/18tRs" target="_blank">Wired Business (Archive)</a></p></li>
	<li class="news"><p><strong>Fun application: </strong> a periodic table of visualization methods. <br> 
	<a href="https://www.visual-literacy.org/periodic_table/periodic_table.html" target="_blank">Visual Literacy</a> </p></li>  
</ol>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var expandableHeaders = document.querySelectorAll('.expandable-header');

    function toggleSection(header) {
      var expandableSection = header.nextElementSibling; // Select the next sibling
      var arrow = header.querySelector('.arrow'); // Select the arrow within the clicked header
      var arrowContainer = header.querySelector('.arrow-container'); // Select the arrow-container within the clicked header

      expandableHeaders.forEach(function (otherHeader) {
        if (otherHeader !== header) {
          var otherExpandableSection = otherHeader.nextElementSibling;
          var otherArrow = otherHeader.querySelector('.arrow');
          var otherArrowContainer = otherHeader.querySelector('.arrow-container');

          otherExpandableSection.classList.remove('active');
          otherArrow.classList.remove('down');
          otherArrowContainer.classList.remove('active');
        }
      });

      expandableSection.classList.toggle('active');
      arrow.classList.toggle('down');
      arrowContainer.classList.toggle('active');
    }

    expandableHeaders.forEach(function (expandableHeader, index) {
      expandableHeader.addEventListener('click', function () {
        toggleSection(this);
      });

      // Automatically open the last section on page load
      if (index === expandableHeaders.length - 1) {
        toggleSection(expandableHeader);

        // Scroll down to the header of the last section
        expandableHeader.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });
</script>

</html>
