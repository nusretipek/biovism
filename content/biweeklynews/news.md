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
			max-height: 3000px; /* Adjust the maximum height as needed */
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


<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 7 | 03 Apr 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<h4>AI /ML</h4>
	<ol>
	  <li class="news"><p>Claude 3 Opus leading the Elo rating of Chatbot Arena. LMSYS Chatbot Arena is a crowdsourced open platform for LLM evals.<br><a href="https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard" target="_blank">Hugging Face</a></p></li>
		<li class="news"><p>SiMBA: Simplified Mamba-Based Architecture for Vision and Multivariate Time series. SiMBA outperforms existing State Space Models (SSMs), bridging the performance gap with state-of-the-art transformers.<br><a href="https://arxiv.org/abs/2403.15360" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Track Everything Everywhere Fast and Robustly. A substantial improvement in training speed (more than 10 times faster), robustness, and accuracy in tracking over the SoTA optimization-based method OmniMotion.<br><a href="https://timsong412.github.io/FastOmniTrack/" target="_blank">GitHub (FastOmniTrack)</a></p></li>
		<li class="news"><p>ViTAR: Vision Transformer with Any Resolution. VITAR demonstrates impressive adaptability, achieving 83.3% top-1 accuracy at a 1120x1120 resolution and 80.4% accuracy at a 4032x4032 resolution, all while reducing computational costs.<br><a href="https://arxiv.org/abs/2403.18361" target="_blank">arXiv</a></p></li>
	  <li class="news"><p>Moirai: A Time Series Foundation Model for Universal Forecasting, offering universal forecasting capabilities.<br><a href="https://blog.salesforceairesearch.com/moirai/" target="_blank">Salesforce AI Research</a></p></li>
		<li class="news"><p>NonlinearSolve.jl: High-Performance and Robust Solvers for Systems of Nonlinear Equations in Julia.<br><a href="https://arxiv.org/abs/2403.16341" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Hybrid-Net: Real-time audio source separation, generate lyrics, chords, beat.<br><a href="https://github.com/DoMusic/Hybrid-Net" target="_blank">GitHub (DoMusic)</a></p></li>
		<li class="news"><p>AI generates high-quality images 30 times faster in a single step. Novel method makes tools like Stable Diffusion and DALL-E-3 faster by simplifying the image-generating process to a single step while maintaining or enhancing image quality.<br><a href="https://news.mit.edu/2024/ai-generates-high-quality-images-30-times-faster-single-step-0321" target="_blank">MIT News</a></p></li>
		<li class="news"><p>PERL: Parameter Efficient Reinforcement Learning from Human Feedback; reward model training and reinforcement learning using LoRA from Google Research.<br><a href="https://arxiv.org/abs/2403.10704" target="_blank">arXiv</a></p></li>
		<li class="news"><p>From Google DeepMind, Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers. Vid2Robot understands the task from videos and can perform in unseen settings.<br><a href="https://vid2robot.github.io" target="_blank">GitHub (vid2robot)</a></p></li>
		<li class="news"><p>Towards 1-bit Machine Learning Models. Recent works on extreme low-bit quantization such as BitNet and 1.58 bit have attracted a lot of attention in the machine learning community. The main idea is that matrix multiplication with quantized weights can be implemented without multiplications, which can potentially be a game-changer in terms of compute efficiency of large machine learning models.<br><a href="https://mobiusml.github.io/1bit_blog/" target="_blank">GitHub (1bit_blog)</a></p></li>
	</ol>
<h4>Technology</h4>
	<ol>
	  <li class="news"><p>Inkjets are for more than just printing, they can build DNA arrays, 3D structures, and much more.<br><a href="https://spectrum.ieee.org/inkjet-printer" target="_blank">IEEE Spectrum</a></p></li>
		<li class="news"><p>‘A landmark moment’: scientists use AI to design antibodies from scratch. Modified protein-design tool could make it easier to tackle challenging drug targets — but AI antibodies are still a long way from reaching the clinic.<br><a href="https://www.nature.com/articles/d41586-024-00846-7" target="_blank">Nature</a></p></li>
		<li class="news"><p>Engineers find a new way to convert carbon dioxide into useful products.<br><a href="https://news.mit.edu/2024/engineers-find-new-way-convert-carbon-dioxide-useful-products-0327" target="_blank">MIT news</a></p></li>
		<li class="news"><p>You can make a song for any moment in any major language with just a few short words. v3 is the first model capable of producing radio-quality music.<br><a href="https://www.suno.ai/blog/v3" target="_blank">Suno AI</a></p></li>
	  <li class="news"><p>WindSpider launches a step-changing crane for use on increasingly larger wind turbines. The self-erecting crane has no weight or height limitations and can be used in very windy locations. The new solution significantly reduces the wind turbine’s life cycle costs for the global wind industry.<br><a href="https://windspider.com/gigantic-aluminium-spiders/" target="_blank">Wind Spider</a></p></li>
	</ol>
<h4>Miscellaneous</h4>
	<ol>
	  <li class="news"><p>Algorithmic improvement is a key factor driving the advance of AI. An analysis showing that since 2012 the amount of compute needed to train a neural net to the same performance on ImageNet classification has been decreasing by a factor of 2 every 16 months. Compared to 2012, it now takes 44 times less compute to train a neural network to the level of AlexNet (by contrast, Moore’s Law would yield an 11x cost improvement over this period). Our results suggest that for AI tasks with high levels of recent investment, algorithmic progress has yielded more gains than classical hardware efficiency.<br><a href="https://openai.com/research/ai-and-efficiency" target="_blank">OpenAI</a></p></li>
	  <li class="news"><p>AI-generated food images look tastier than real ones.<br><a href="https://www.ox.ac.uk/news/2024-03-15-ai-generated-food-images-look-tastier-real-ones" target="_blank">University of Oxford News</a></p></li>
		<li class="news"><p>Memories are made by breaking DNA and fixing it; Nerve cells form long-term memories with the help of an inflammatory response, study in mice finds.<br><a href="https://www.nature.com/articles/d41586-024-00930-y" target="_blank">Nature</a></p></li>
		<li class="news"><p>These Plants Could Mine Valuable Metals From the Soil With Their Roots.<br><a href="https://singularityhub.com/2024/03/28/these-plants-could-mine-crucial-battery-materials-from-the-soil-with-their-roots/" target="_blank">Singularity Hub</a></p></li>
		<li class="news"><p>Start using ChatGPT instantly, making it easier for people to experience the benefits of AI without needing to sign up. It also means protection against any upcoming age verification laws.<br><a href="https://openai.com/blog/start-using-chatgpt-instantly" target="_blank">OpenAI</a></p></li>
	</ol>
</div>


<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 6 | 20 Mar 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<h4>AI /ML</h4>
	<ol>
	    <li class="news"><p>New algorithm unlocks high-resolution insights for computer vision. <b>FeatUp</b>, developed by MIT CSAIL researchers, boosts the resolution of any deep network or visual foundation for computer vision systems.<br><a href="https://news.mit.edu/2024/featup-algorithm-unlocks-high-resolution-insights-computer-vision-0318" target="_blank">MIT News</a> & <a href="https://mhamilton.net/featup.html" target="_blank">Mark T. Hamilton (Paper)</a></p></li>
		<li class="news"><p>A generalist AI agent for 3D virtual environments. Google DeepMind present new research on a Scalable Instructable Multiworld Agent (SIMA) that can follow natural-language instructions to carry out tasks in a variety of video game settings.<br><a href="https://deepmind.google/discover/blog/sima-generalist-ai-agent-for-3d-virtual-environments/" target="_blank">Google DeepMind</a></p></li>
		<li class="news"><p>Introducing the next generation of Claude; which sets new industry benchmarks across a wide range of cognitive tasks. All Claude 3 models show increased capabilities in analysis and forecasting, nuanced content creation, code generation, and conversing in non-English languages like Spanish, Japanese, and French.<br><a href="https://www.anthropic.com/news/claude-3-family" target="_blank">Anthropic</a></p></li>
		<li class="news"><p>Cappy: Outperforming and boosting large multi-task language models with a small scorer. Cappy as a pre-trained model can potentially be used in other creative ways beyond on single LLMs.<br><a href="https://blog.research.google/2024/03/cappy-outperforming-and-boosting-large.html" target="_blank">Google Research</a></p></li>
	  <li class="news"><p>Stealing Part of a Production Language Model. It was possible to steal part of OpenAI’s ChatGPT or Google’s PaLM-2 (up to an affine transformation) by making queries to their public APIs. It was a known vulnerability of deployed ML models since 2016; "Stealing Machine Learning Models via Prediction APIs".<br><a href="https://not-just-memorization.github.io/partial-model-stealing.html" target="_blank">GitHub (not-just-memorization)</a> & <a href="https://arxiv.org/abs/1609.02943" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking. A generalization of Self-Taught Reasoner (STaR) in which LMs learn to generate rationales at each token to explain future text, improving their predictions.<br><a href="https://arxiv.org/abs/2403.09629" target="_blank">arXiv</a></p></li>
	  <li class="news"><p>Design2Code: How Far Are We From Automating Front-End Engineering. An open-source Design2Code-18B model that successfully matches the performance of Gemini Pro Vision.<br><a href="https://salt-nlp.github.io/Design2Code/" target="_blank">GitHub(salt-nlp)</a></p></li>
		<li class="news"><p>Large language models surpass human experts in predicting neuroscience results. LLMs trained on the vast scientific literature could potentially integrate noisy yet interrelated findings to forecast novel results better than human experts.<br><a href="https://arxiv.org/abs/2403.03230" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Amazon reveals Chronos: Learning the Language of Time Series. A simple yet effective framework for pretrained probabilistic time series models.<br><a href="https://arxiv.org/abs/2403.07815" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Using generative AI to improve software testing; MIT spinout DataCebo helps companies bolster their datasets by creating synthetic data that mimic the real thing.<br><a href="https://news.mit.edu/2024/using-generative-ai-improve-software-testing-datacebo-0305" target="_blank">MIT News</a></p></li>
		<li class="news"><p>Nvidia Unveils Blackwell, Its Next GPU; a big boost in AI training performance, an even bigger one for AI inference.<br><a href="https://spectrum.ieee.org/nvidia-blackwell" target="_blank">IEEE Spectrum</a></p></li>
	</ol>
<h4>Technology</h4>
	<ol>
	  <li class="news"><p>Nvidia Announces GR00T, a Foundation Model For Humanoids. GR00T is intended to provide a starting point for specific humanoid robots to do specific tasks.<br><a href="https://spectrum.ieee.org/nvidia-gr00t-ros" target="_blank">IEEE Spectrum</a></p></li>
	  <li class="news"><p>3D microprinter hacked to fabricate transistors for bioelectronics. The speed of innovation in bioelectronics and critical sensors gets a new boost with the unveiling of a technique for fast-prototyping of devices.<br><a href="https://www.kth.se/en/om/nyheter/centrala-nyheter/3d-microprinter-hacked-to-fabricate-transistors-for-bioelectronics-1.1319335" target="_blank">KTH</a></p></li>
		<li class="news"><p>Giant "sand battery" holds a week's heat for a whole town. It packs 1 MW of power and a capacity of up to 100 MWh of thermal energy for use during those cold polar winters.<br><a href="https://newatlas.com/energy/sand-battery-finland/" target="_blank">New Atlas</a></p></li>
		<li class="news"><p>Figure AI presents full conversations with Figure 01 with OpenAI partnership.<br><a href="https://twitter.com/coreylynch/status/1767927194163331345" target="_blank">Twitter (coreylynch)</a></p></li>
		<li class="news"><p>Mercedes Hires Humanoid Robots to Work at Its Factories. Apptronik's Apollo robots are 5'8 in height and will complete manual labor tasks like bringing parts to the Mercedes-Benz assembly line.<br><a href="https://www.pcmag.com/news/mercedes-hires-humanoid-robots-work-at-its-factories" target="_blank">PC Magazine</a></p></li>
	</ol>
<h4>Miscellaneous</h4>
	<ol>
	  <li class="news"><p>Bumblebees socially learn behaviour too complex to innovate alone.  Social learning might permit the acquisition of behaviours too complex to ‘re-innovate’ through individual learning.<br><a href="https://www.nature.com/articles/s41586-024-07126-4" target="_blank">Nature</a></p></li>
		<li class="news"><p>Adaptive immune responses are larger and functionally preserved in a hypervaccinated individual. What happens if vaccinated 217 times against SARS-CoV-2 within a period of 29 months?<br><a href="https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(24)00134-8/fulltext" target="_blank">The Lancet</a></p></li>
		<li class="news"><p>Apple’s AI ambitions could include Google or OpenAI; The iPhone-maker is in ‘active’ talks to bring Gemini to the iPhone, and has also considered using ChatGPT.<br><a href="https://www.theverge.com/2024/3/18/24104626/apple-license-google-gemini-generative-ai-openai-chatgpt" target="_blank">The Verge</a></p></li>
		<li class="news"><p>Tick-killing pill shows promising results in human trial;  the pill would be a new weapon against Lyme disease.<br><a href="https://arstechnica.com/science/2024/03/tick-killing-pill-shows-promising-results-in-human-trial/" target="_blank">Ars Technica</a></p></li>
	</ol>
<h4>Fun</h4>
  <ol>
	  <li class="news"><p><b>Paper:</b> "Certainly, here is a possible introduction for your topic" in scientific paper... Check first line of the introduction!<br><a href="https://www.sciencedirect.com/science/article/pii/S2468023024002402" target="_blank">Elsevier (Surfaces and Interfaces)</a></p></li>
		<li class="news"><p><b>Movie List:</b> The Mathematical Movie Database.<br><a href="https://www.qedcat.com/moviemath/index.html#1" target="_blank">QEDCAT</a></p></li>
	</ol>
</div>


<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 5 | 06 Mar 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<h4>AI /ML</h4>
	<ol>
	  <li class="news"><p>Stable Diffusion 3 in early preview, text-to-image model with greatly improved performance in multi-subject prompts, image quality, and spelling abilities. While the model is not yet broadly available, today, you can subscribe the waitlist for an early preview.  New Multimodal Diffusion Transformer (MMDiT) architecture uses separate sets of weights for image and language representations, which improves text understanding and spelling capabilities compared to previous versions of SD3. Stable Diffusion 3 outperforms state-of-the-art text-to-image generation systems such as DALL·E 3, Midjourney v6, and Ideogram v1 in typography and prompt adherence, based on human preference evaluations.<br><a href="https://stability.ai/news/stable-diffusion-3" target="_blank">Stability AI</a> & <a href="https://stability.ai/news/stable-diffusion-3-research-paper" target="_blank">Stability AI Research Paper</a></p></li>
		<li class="news"><p>YOLOv9 is here; "Learning What You Want to Learn Using Programmable Gradient Information“. New version introduces concept of Programmable Gradient Information (PGI) and Generalized Efficient Layer Aggregation Network (GELAN). It can be used to obtain complete information, so that train-from-scratch models can achieve better results than state-of-the-art models pre-trained using large datasets.<br><a href="https://arxiv.org/abs/2402.13616" target="_blank">arXiv: Computer Science</a> & <a href="https://github.com/WongKinYiu/yolov9" target="_blank">GitHub: WongKinYiu</a></p></li>
		<li class="news"><p>Google has a new 'woke' AI problem with Gemini — and it's going to be hard to fix. The latest version of Google's Gemini artificial intelligence (AI) will frequently produce images of Black, Native American and Asian people when prompted – but refuses to do the same for White people.  It wouldn't promote meat; and said it wouldn't help promote fossil fuels... How about the historical facts? George Washington displayed as a black person. In my opinion, Generative AI should be actually unbiased and it should not skew numbers in either direction, or for anyone.<br><a href="https://www.businessinsider.com/google-gemini-woke-images-ai-chatbot-criticism-controversy-2024-2?r=US&IR=T" target="_blank">Business Insider</a> & <a href="https://www.foxbusiness.com/media/google-apologizes-new-gemini-ai-refuses-show-pictures-achievements-white-people" target="_blank">Fox Business</a></p></li>  
		<center><img src="aimeme.jpg" alt="Gemini Meme" width="38%"></center><br>
		<li class="news"><p>Video ReCap: Recursive Captioning of Hour-Long Videos from Meta AI. A model that can process video inputs of dramatically different lengths (from 1 second to 2 hours) and output video captions at multiple hierarchy levels.<br><a href="https://sites.google.com/view/vidrecap" target="_blank">Video ReCap (Google Sites)</a></p></li>
		<li class="news"><p>From Google DeepMind: Genie (Generative Interactive Environments). Genie is a foundation world model trained from Internet videos that can generate an endless variety of playable (action-controllable) worlds from synthetic images, photographs, and even sketches.<br><a href="https://sites.google.com/view/genie-2024/home" target="_blank">Google DeepMind</a></p></li>
		<li class="news"><p>LENS Project: a tool is to provide a quick overview of the main concepts (dictionary of features) employed by a large vision model. Promising development in explainable AI (XAI).<br><a href="https://serre-lab.github.io/Lens/" target="_blank">GitHub: Serre Lab</a></p></li>
		<li class="news"><p>Elon Musk sues OpenAI over AI threat: OpenAI is not so open now, Musk claims, following the closed-source release of the company's artificial general intelligence technology under Microsoft.<br><a href="https://www.courthousenews.com/elon-musk-sues-openai-over-ai-threat/" target="_blank">Courthouse News Service</a></p></li>
		<li class="news"><p>Approaching Human-Level Forecasting with Language Models. "On average, the system nears the crowd aggregate of competitive forecasters, and in some settings surpasses it. Our work suggests that using LMs to forecast the future could provide accurate predictions at scale and help to inform institutional decision making.".<br><a href="https://arxiv.org/abs/2402.18563" target="_blank">arXiv</a></p></li>
  </ol>
<h4>Technology</h4>
	<ol>
	  <li class="news"><p>Samsung unveils the Galaxy Ring as a way to 'simplify everyday wellness'. The Galaxy Ring will be part of the Samsung Health ecosystem and be compatible with the Galaxy Watch. We'll learn more in the months ahead, including the exact sensor suite, pricing and sale date.<br><a href="https://www.engadget.com/samsung-unveils-the-galaxy-ring-as-a-way-to-simplify-everyday-wellness-080134421.html" target="_blank">engadget</a></p></li>
	  <li class="news"><p>A new optical metamaterial makes true one-way glass possible. "Just imagine having a window with that glass in your house, office, or car. Regardless of the brightness outside, people wouldn’t be able to see anything inside, while you would enjoy a perfect view from your window".<br><a href="https://www.aalto.fi/en/news/a-new-optical-metamaterial-makes-true-one-way-glass-possible" target="_blank">Aalto University</a></p></li>
		<li class="news"><p>New time crystal stable for more than 40 minutes: Nobel Prize on the way?  A team of physicists has now built the most robust time crystal ever using solid-state physics.<br><a href="https://www.youtube.com/watch?v=sTbYKPP7q3E" target="_blank">YouTube: Science News</a></p></li>
		<li class="news"><p>Mind-reading devices are revealing the brain’s secrets. Implants and other technologies that decode neural activity can restore people’s abilities to move and speak — and help researchers to understand how the brain works.<br><a href="https://www.nature.com/articles/d41586-024-00481-2" target="_blank">Nature</a></p></li>
	  <li class="news"><p>Your fingerprints can be recreated from the sounds made when you swipe on a touchscreen — Chinese and US researchers show new side channel can reproduce fingerprints to enable attacks. Researchers claim they can successfully attack up to 27.9% of partial fingerprints.<br><a href="https://www.tomshardware.com/tech-industry/cyber-security/your-fingerprints-can-be-recreated-from-the-sounds-made-when-you-swipe-on-a-touchscreen-researchers-new-side-channel-attack-can-reproduce-partial-fingerprints-to-enable-attacks" target="_blank">Tom's  Hardware</a></p></li>
	</ol>
<h4>Miscellaneous</h4>
	<ol>
	  <li class="news"><p>The startup Figure AI Inc. appears to be in the center of attention soon with developing human-like robots. Jeff Bezos and Nvidia join OpenAI and Microsoft in backing a humanoid robot unicorn valued at $2 billion.<br><a href="https://fortune.com/2024/02/23/jeff-bezos-nvidia-openai-microsoft-robot-unicorn-figureai-funding-round/" target="_blank">Fortune</a> & <a href="https://twitter.com/Figure_robot/status/1762184059399377370" target="_blank">Twitter: Figure_robot</a></p></li>
		<li class="news"><p>Although not so new, the Apache Superset is evolving to be the de facto open-source modern data exploration and visualization platform. Whether it will dethrone Tableau or not, is still debatable.<br><a href="https://superset.apache.org" target="_blank">Apache Superset</a> & <a href="https://www.mergeyourdata.com/blog/is-tableau-dead-the-future-of-tableau" target="_blank">MergeYourData</a></p></li>  
		<li class="news"><p>Mounting research shows that COVID-19 leaves its mark on the brain, including with significant drops in IQ scores. Those who had mild and resolved COVID-19 showed cognitive decline equivalent to a three-point loss of IQ.<br><a href="https://theconversation.com/mounting-research-shows-that-covid-19-leaves-its-mark-on-the-brain-including-with-significant-drops-in-iq-scores-224216" target="_blank">The Conversation</a></p></li>
		<li class="news"><p>Good News: Small Nuclear Thorium Reactors are Coming to Europe.<br><a href="https://www.youtube.com/watch?v=Tf4XahwtJUk" target="_blank">Science News</a></p></li>
		<li class="news"><p>Apple to Wind Down Electric Car Effort After Decadelong Odyssey, employees on some car teams will move to Apple’s AI division (generative AI).<br><a href="https://www.bloomberg.com/news/articles/2024-02-27/apple-cancels-work-on-electric-car-shifts-team-to-generative-ai" target="_blank">Bloomberg</a></p></li>
		<li class="news"><p>Spontaneous playful teasing in four great ape species; new research shows that as playful teasing is present in all extant great ape genera, it is likely that the cognitive prerequisites for joking evolved in the hominoid lineage at least 13 million years ago.<br><a href="https://royalsocietypublishing.org/doi/10.1098/rspb.2023.2345" target="_blank">Proceedings of the Royal Society B</a></p></li>
	</ol>
<h4>Fun</h4>
  <ol>
	  <li class="news"><p><b>Tutorial:</b> Learn to read Korean in 15 minutes.<br><a href="https://www.ryanestrada.com/learntoreadkoreanin15minutes/" target="_blank">Ryan Estrada</a></p></li>
		<li class="news"><p><b>Package:</b> Daft is a distributed query engine for large-scale data processing in Python and is implemented in Rust. Give it a try over Pandas.<br><a href="https://github.com/Eventual-Inc/Daft" target="_blank">GitHub: Eventual Computing</a></p></li>
	</ol>
</div>


<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 4 | 21 Feb 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<h4>AI /ML</h4>
	<ol>
		<li class="news"><p>Sora is an AI model that can create realistic and imaginative scenes from text instructions (for now, only a minute of high fidelity video). Technically; text-conditional diffusion models jointly on videos and images of variable durations, resolutions and aspect ratios. "If you think OpenAI Sora is a creative toy like DALLE, ... think again. Sora is a data-driven physics engine. It is a simulation of many worlds, real or fantastical. The simulator learns intricate rendering, "intuitive" physics, long-horizon reasoning, and semantic grounding, all by some denoising and gradient maths." <br><a href="https://twitter.com/DrJimFan/status/1758210245799920123" target="_blank">Twitter (DrJimFan)</a> & <a href="https://openai.com/sora" target="_blank">OpenAI</a> & <a href="https://www.youtube.com/watch?v=nbPbK1xYSNY" target="_blank">YouTube (Two Minute Papers)</a></p></li>
    <li class="news"><p>Google's "Bard" recently became "Gemini". Gemini 1.5 is the next generation model that delivers dramatically enhanced performance with long-context understanding across modalities up to 1M tokens (meaning 1h video or 30k lines code) via new Mixture-of-Experts (MoE) architecture. As an impressive example; Gemini 1.5 learns to translate from English to <a href="https://en.wikipedia.org/wiki/Kalamang_language" target="_blank">Kalamang language</a> purely in context, following a full linguistic manual at inference time. Kalamang is a language spoken by fewer than 200 speakers in western New Guinea. It appears that Gemini 1.5 overperform OpenAI GPT-4 in SOTA.<br><a href="https://blog.google/products/gemini/bard-gemini-advanced-app/" target="_blank">Google (Blog)</a> & <a href="https://blog.google/technology/ai/google-gemini-next-generation-model-february-2024/#gemini-15" target="_blank">Google (Blog)</a></p></li>  
    <li class="news"><p>From Google Research "Grandmaster-Level Chess Without Search". The researchers took 10M human-human chess games from an online chess arena, then asked the Stockfish 16 engine for its estimate of the "winning probability" for this board+move, based on Stockfish's analysis of up to 0.05 seconds. They then trained a transformer-based model whose input is the board position+move, and the target output is the winning probability of the move.<br><a href="https://arxiv.org/abs/2402.04494" target="_blank">arXiv</a> & <a href="https://gist.github.com/yoavg/8b98bbd70eb187cf1852b3485b8cda4f" target="_blank">GitHub Gist (yoavg)</a></p></li>
		<li class="news"><p>LLM Agents can Autonomously Hack Websites. Using GPT-4, it is possible to hack websites, performing tasks as complex as blind database schema extraction and SQL injections without human feedback.<br><a href="https://arxiv.org/abs/2402.06664" target="_blank">arXiv</a></p></li>
		<li class="news"><p>Lag-Llama: Towards Foundation Models for Probabilistic Time Series Forecasting: first open-source foundation model for time series forecasting.<br><a href="https://arxiv.org/abs/2310.08278" target="_blank">arXiv</a> & <a href="https://github.com/time-series-foundation-models/lag-llama" target="_blank">GitHub (lag-llama)</a></p></li>  
		<li class="news"><p>How symmetry can come to the aid of machine learning; Exploiting the symmetry within datasets can decrease the amount of data needed for training neural networks.<br><a href="https://news.mit.edu/2024/how-symmetry-can-aid-machine-learning-0205" target="_blank">MIT News</a></p></li>
		<li class="news"><p>A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts from Google DeepMind.<br><a href="https://read-agent.github.io" target="_blank">GitHub (read-agent)</a></p></li>
		<li class="news"><p>Video Joint Embedding Predictive Architecture (V-JEPA): The next step toward Yann LeCun’s vision of advanced machine intelligence (AMI) by Meta AI. Yet another novelty in teaching machines to understand and model the physical world just by watching videos.<br><a href="https://ai.meta.com/blog/v-jepa-yann-lecun-ai-model-video-joint-embedding-predictive-architecture/" target="_blank">Meta AI</a></p></li>
		<li class="news"><p>Universal Manipulation Interface (UMI) In-The-Wild Robot Teaching Without In-The-Wild Robots. It is a framework that enables learning capable and generalizable manipulation policies directly from in-the-wild human demonstrations.<br><a href="https://umi-gripper.github.io" target="_blank">GitHub (umi-gripper)</a></p></li>
		<li class="news"><p>SERL: A Software Suite for Sample-Efficient Robotic Reinforcement Learning.  Ready-to-use software suite for robotic RL, trains policies in just 25 to 50 minutes, outperforming previous benchmarks with high success rates and robustness.<br><a href="https://serl-robot.github.io" target="_blank">GitHub (serl-robot)</a></p></li>
		<li class="news"><p>Tiny Quadrotor Learns to Fly in 18 Seconds NYU and TII researchers get robots into the air with fast simulations on a consumer laptop.<br><a href="https://spectrum.ieee.org/drone-quadrotor" target="_blank">IEEE Spectrum</a></p></li>
  </ol>
<h4>Technology</h4>
	<ol>
	  <li class="news"><p>A team of University of Wisconsin–Madison scientists has developed the first 3D-printed brain tissue that can grow and function like typical brain tissue. First 3D-printed functional human brain tissue grows like the real thing.<br><a href="https://news.wisc.edu/uw-madison-researchers-first-to-3d-print-functional-human-brain-tissue/" target="_blank">University of Wisconsin–Madison</a> & <a href="https://newatlas.com/science/novel-3d-printing-technique-brain-tissue-functional-neurons/" target="_blank">New Atlas</a></p></li>
		<li class="news"><p>Mapping the Brain: Google Research is making exciting advances on understanding how our own brains work and how we think.<br><a href="https://www.youtube.com/watch?v=aB_ZmAM3tv8" target="_blank">YouTube (Google Brain)</a></p></li>
		<li class="news"><p>Europe’s deepest mine to become giant gravity battery; potential to store up to 2 MW of energy.<br><a href="https://www.independent.co.uk/tech/gravity-battery-mine-renewable-energy-b2492087.html" target="_blank">Independent</a></p></li>
		<li class="news"><p>Smartphone screens are about to become speakers. Piezoelectrics enable displays to provide both high-quality audio and touch feedback.<br><a href="https://spectrum.ieee.org/piezoelectric-speakers" target="_blank">IEEE Spectrum</a></p></li>
		<li class="news"><p>New way of harvesting renewable energy, 1.2 MW tidal kite is now exporting power to the grid.<br><a href="https://newatlas.com/energy/minesto-tidal-kite/" target="_blank">New Atlas</a></p></li>		
	  <li class="news"><p>$5 device accurately tests for breast cancer in under 5 seconds.<br><a href="https://pubs.aip.org/avs/jvb/article/42/2/023202/3262988/High-sensitivity-saliva-based-biosensor-in" target="_blank">Journal of Vacuum Science & Technology B</a></p></li>
	</ol>
<h4>Miscellaneous</h4>
	<ol>
		<li class="news"><p><b>Be careful: </b> Deepfake fraud is already here. It’s becoming more common, more convincing, and more dangerous.<br><a href="https://twitter.com/ai_ctrl/status/1757109466992988622" target="_blank">Twitter (Control AI)</a></p></li>
		<li class="news"><p>Each GPT costs between 25x and 100x the last one and Sam Altman Wants $7 Trillion. Although it is unlikely that he can get this amount, the GPT-8 appears to be impossible to build with the current state of hardware.<br><a href="https://www.astralcodexten.com/p/sam-altman-wants-7-trillion" target="_blank">Astral Codex Ten</a></p></li>
		<li class="news"><p>Turbocharged CAR-T cells melt tumours in mice - using a trick from cancer cells (Immune cells armed with a mutation first identified in cancer cells gain potency but don’t turn cancerous themselves).<br><a href="https://www.nature.com/articles/d41586-024-00305-3" target="_blank">Nature</a></p></li>
		<li class="news"><p>AI Is Learning to Decode the "Language" of Chickens; opening doors to a new era in animal-human interaction.<br><a href="https://singularityhub.com/2024/02/06/this-ai-is-learning-to-decode-the-language-of-chickens/" target="_blank">Singularity Hub</a></p></li>
		<li class="news"><p>How long is “forever”? When it comes to digital media, forever could be as close as a couple of months away. Sony is erasing digital libraries that were supposed to be accessible “forever”.<br><a href="https://arstechnica.com/culture/2024/02/funimation-dvds-included-forever-available-digital-copies-forever-ends-april-2/" target="_blank">arsTECHNICA</a></p></li>
	</ol>
<h4>Fun</h4>
  <ol>
		<li class="news"><p><b>Post:</b> Introduction to Thompson Sampling: the Bernoulli bandit.<br><a href="https://gdmarmerola.github.io/ts-for-bernoulli-bandit/" target="_blank">GitHub (gdmarmerola)</a></p></li>
		<li class="news"><p><b>Project:</b> Explore interesting places nearby listed on Wikipedia.<br><a href="https://en.nearbywiki.org/map" target="_blank">NearbyWiki</a></p></li>
	</ol>
</div>


<h3 class="expandable-header"><span class="arrow-container"><strong>Newsletter 3 | 07 Feb 2024</strong><span class="arrow"></span></span></h3>
<div class="expandable-section">
<ol>
  <li class="news"><p>A decoder-only foundation model for time-series forecasting. Google introduce TimesFM, a single forecasting model pre-trained on a large time-series corpus of 100 billion real world time-points. Compared to the latest large language models (LLMs), TimesFM is much smaller (200M parameters), yet we show that even at such scales, its zero-shot performance on a variety of unseen datasets of different domains and temporal granularities come close to the state-of-the-art supervised approaches trained explicitly on these datasets.<br><a href="https://blog.research.google/2024/02/a-decoder-only-foundation-model-for.html" target="_blank">Google Research</a> & <a href="https://arxiv.org/pdf/2310.10688.pdf" target="_blank">arXiv</a> </p></li>
  <li class="news"><p>Generative expressive robot behaviors using large language models by Google Deepmind.<br><a href="https://generative-expressive-motion.github.io" target="_blank">GitHub (Generative Expressive Motion)</a></p></li>
  <li class="news"><p>A Benchmark for Real-World Planning with Language Agents by Meta AI; “Comprehensive evaluations show that the current language agents are not yet capable of handling such complex planning tasks-even GPT-4 only achieves a success rate of 0.6%. Language agents struggle to stay on task, use the right tools to collect information, or keep track of multiple constraints.”<br><a href="https://osu-nlp-group.github.io/TravelPlanner/" target="_blank">GitHub (OSU NLP Group)</a></p></li>
  <li class="news"><p>MobileDiffusion: Rapid text-to-image generation on-device. Google introduce a novel approach with the potential for rapid text-to-image generation on-device. MobileDiffusion is an efficient latent diffusion model specifically designed for mobile devices.<br><a href="https://blog.research.google/2024/01/mobilediffusion-rapid-text-to-image.html" target="_blank">Google Research</a></p></li>
  <li class="news"><p>LUMIERE: A Space-Time Diffusion Model for Video Generation for synthesizing videos that portray realistic, diverse and coherent motion -- a pivotal challenge in video synthesis.<br><a href="https://lumiere-video.github.io" target="_blank">GitHub (Google Research)</a></p></li>
  <li class="news"><p>DeepSeek Coder comprises a series of code language models trained from scratch on both 87% code and 13% natural language in English and Chinese, with each model pre-trained on 2T token  over more than 80 programming language. State-of-the-Art performance among open code models while open source and free for research and commercial use.<br><a href="https://deepseekcoder.github.io" target="_blank">GitHub</a></p></li>
  <li class="news"><p>SUPIR:  Revolutionizing image restoration with cutting-edge large-scale AI. Text-driven, intelligent restoration, blending AI technology with creativity to give every image a brand new life.<br><a href="https://supir.xpixel.group" target="_blank">XPixel</a></p></li>
  <li class="news"><p>OK-Robot: An open, modular framework for zero-shot, language conditioned pick-and-drop tasks in arbitrary homes.<br><a href="https://ok-robot.github.io" target="_blank">GitHub</a></p></li>
  <li class="news"><p>Roboflow introduce Supervision: open-source toolkit for any computer vision project. Whether you want to process a video, draw a detection on a frame, or convert labels from one format to another, Supervision includes easy to use scripts.<br><a href="https://github.com/roboflow/supervision?tab=readme-ov-file" target="_blank">GitHub (roboflow)</a></p></li>
  <li class="news"><p>Can AI Unlock the Secrets of the Ancient World? Vesuvius Challenge to solve the ancient problem of the Herculaneum Papyri, a library of scrolls that were flash-fried by the eruption of Mount Vesuvius in 79 AD. Today we are overjoyed to announce that our crazy project has succeeded. After 2000 years, we can finally read the scrolls.<br><a href="https://archive.is/08IxN#selection-1507.0-1507.47" target="_blank">Bloomberg (Archive.is)</a></p></li>
	<li class="news"><p>Next frontier in AI: Learning World Models. Path to artificial general intelligence (AGI) is leading to AI systems that builds an internal representation of an environment, and uses it to simulate future events within that environment.<br><a href="https://www.youtube.com/watch?v=GbzNb6a6_SQ" target="_blank">YouTube (Elicit)</a></p></li>
  <li class="news"><p>Programming light propagation creates highly efficient neural networks. Programming light propagation creates highly efficient neural networks.<br><a href="https://spie.org/news/programming-light-propagation-creates-highly-efficient-neural-networks#_=_" target="_blank">Society for Optics and Photonics (SPIE)</a></p></li>
  <li class="news"><p>Researchers Approach New Speed Limit for Seminal Problem: Integer linear programming. Now researchers have found a much faster way to do it.<br><a href="https://www.quantamagazine.org/researchers-approach-new-speed-limit-for-seminal-problem-20240129/" target="_blank">Quanta Magazine</a></p></li>
  <li class="news"><p>How AI is changing gymnastics judging? Proponents say the AI-powered Judging Support System will promote fairness and transparency in the sport.<br><a href="https://www.technologyreview.com/2024/01/16/1086498/ai-gymnastics-judging-jss-world-championships-antwerp-paris-olympics/" target="_blank">MIT Technology Review</a></p></li>
  <li class="news"><p>Invasive cervical cancer incidence following bivalent human papillomavirus vaccination: a population-based observational study of age at immunization, dose, and deprivation. Analysis from Scotland shows for women vaccinated at 12 or 13 years of age, there is no prevalance of cervical cancer.<br><a href="https://academic.oup.com/jnci/advance-article-abstract/doi/10.1093/jnci/djad263/7577291?login=false" target="_blank">The Journal of the National Cancer Institute</a></p></li>
  <li class="news"><p>Fiber Optics Bring You Internet. Now They’re Also Listening to Trains. Distributed acoustic sensing already applied to detect earthquakes and insects. It appears that the applications grow rapidly.<br><a href="https://archive.is/1q62p" target="_blank">WIRED (Archive.is)</a></p></li>
  <li class="news"><p>AI model flags high-risk pancreatic cancer patients 18 months before diagnosis. Novel approach caught 3.5 times as many cases than current screening guidelines would have for 40-plus group.<br><a href="https://news.harvard.edu/gazette/story/2024/02/ai-model-flags-high-risk-pancreatic-cancer-patients-18-months-before-diagnosis/" target="_blank">The Harvard Gazette</a></p></li>
  <li class="news"><p>Detecting the future of pandemics, sequencing wastewater could be promising: It allows us to monitor millions of people’s disease status at a single site; Inferring the sensitivity of wastewater metagenomic sequencing for pathogen early detection.<br><a href="https://www.medrxiv.org/content/10.1101/2023.12.22.23300450v2" target="_blank">medRxiv</a></p></li>
  <li class="news"><p>Fewer and faster: Global fertility isn't just declining, it's collapsing. If you’re a Millennial or a younger Gen Xer, you’ll probably see the start of a long-term decline in human population due to the global collapse in fertility. That’s something that’s never happened before with Homo sapiens.<br><a href="https://fasterplease.substack.com/p/fewer-and-faster-global-fertility" target="_blank">Substack (fasterplease)</a></p></li>
  <li class="news"><p>Researchers demonstrate rapid 3D printing with liquid metal. Their new technique can produce furniture-sized aluminum parts in only minutes.<br><a href="https://news.mit.edu/2024/researchers-demonstrate-rapid-3d-printing-liquid-metal-0125" target="_blank">MIT News</a></p></li>
  <li class="news"><p>A couple of new features are coming to Google Search, starting with the self-explanatory Circle to Search — but only on a handful of Android phones. Now, you’ll be able to add complex questions to refine your visual search. For example, you can take a picture of a plant, add it to your search, and ask, “How often should I water this?”<br><a href="https://www.theverge.com/2024/1/17/24041198/google-circle-to-search-samsung-galaxy-multi-search-generative-ai" target="_blank">The Verge</a></p></li>
  <li class="news"><p>Twin Labs automates repetitive tasks by letting AI take over your mouse cursor such as reordering items when you’re running out of stock, downloading financial reports across several SaaS products, reaching out to potential prospects and more.<br><a href="https://techcrunch.com/2024/01/31/twin-labs-automates-repetitive-tasks-by-letting-ai-take-over-your-mouse-cursor/" target="_blank">TechCrunch</a></p></li>
  <li class="news"><p><strong>Fun Project:</strong> Plato. Want to learn something new? Turn your YouTube addiction into a fun learning game.<br><a href="https://www.platoedu.org" target="_blank">Plato Education</a></p></li>
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
      if (index === 0) {
        toggleSection(expandableHeader);

        // Scroll down to the header of the last section
        expandableHeader.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });
</script>

</html>
