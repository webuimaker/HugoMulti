+++
title = "Journal"
description = "about this site"
date = "2014-09-27"
slug = "journal"
+++

## Editorial planning with Trello and Zapier

As long as I've been working with editorial teams a content pipeline has been a problem. Knowing the state of a story, its context to those around it, and who has done what, when, is vital in managing a content throughput. Generally, this ﬁgures itself out in a busy, noisy, physical environment. But, the more remote a team becomes, the more challenging it is to communicate on the state of stories.

<div class="row">
	<div class="col-md-2 aside">
		<date>February 9th, 2018 </date>
		Filed in: <a href="#">design</a> <a href="#">editorial</a>  <a href="#">zapier</a>   <a href="#">automation</a> 
		
	</div>
	<div class="col-md-10">
		<p>When I joined <a href="www.embl.org">EMBL</a>  a couple of months ago, this was a problem we had. Content status was done weekly, but a continually available overview by the entire team was not. Nor was there a tool or process to push stories around. As I said, my experience is this is not unique to EMBL. Almost every editorial team I've worked with struggles with this.</p>
		<p><a href="https://twitter.com/thenoyes">Dan</a> and I got our heads together and worked on a process that would fit with the existing team and tools. The team here use Trello extensively for planning, so we started there.</p>
		
		<h2> The one board to rule them all </h2>
		It was important we didn't interfere with existing processes using Trello. The team all use Trello in different, interesting ways to collaborate and manage their content; from ideas to final copy. We needed to integrate with that best we could. This is what we settled on:
		
		<h3>1. A Pre-production Trello Board</h3>
		Once a story is ready to go into the workflow. Meaning it is agreed, planned, assigned to a priority etc, then it is added to the pre-production Trello board. This board is organised by story type: features, updates, press releases. Once a story is complete and ready to publish, it is moved into a column 'Move to Production'. <a href="www.Zapier.com">Zapier</a> then copies the card, with everything in it, over to the Production board. Once that's done, it moves it to an archive list.
		
		<ol>
			<li>Find the Pre-production Trello board</li>
			<li>Find a list on that board called 'Move to Production'</li>
			<li>Find cards moved into that list (this is the trigger to run the whole zap)</li>
			<li>Get information about the card and move it to Production. (In fact, here, I didn't move it but copied it. I wanted a safe-guard in the system so that if something went wrong, there would be a backup)</li>
			<li>Once it's moved, confirm by then moving the card into the archive list.</li>
			<li>Once all that's done, check the card has actually moved.</li>
			<li>Then post to Slack and let everyone know.</li>
		</ol>
	</div>
</div>