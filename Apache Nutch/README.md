Apache Nutch
=======

```HTML


<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
<meta http-equiv="Content-Type" content="text/html;charset=utf-8">
<meta name="robots" content="index,follow">



<body  lang="en" dir="ltr">

<div id="header">

<form id="searchform" method="get" action="/nutch/FrontPage">
<div>
<input type="hidden" name="action" value="fullsearch">
<input type="hidden" name="context" value="180">
<label for="searchinput">Search:</label>
<input id="searchinput" type="text" name="value" value="" size="20"
    onfocus="searchFocus(this)" onblur="searchBlur(this)"
    onkeyup="searchChange(this)" onchange="searchChange(this)" alt="Search">
<input id="titlesearch" name="titlesearch" type="submit"
    value="Titles" alt="Search Titles">
<input id="fullsearch" name="fullsearch" type="submit"
    value="Text" alt="Search Full Text">
</div>
</form>
<script type="text/javascript">
<!--// Initialize search form
var f = document.getElementById('searchform');
f.getElementsByTagName('label')[0].style.display = 'none';
var e = document.getElementById('searchinput');
searchChange(e);
searchBlur(e);
//-->
</script>

<div id="logo"><a href="/nutch/FrontPage">Nutch Wiki</a></div>
<div id="username"><a href="/nutch/FrontPage?action=login" id="login" rel="nofollow">Login</a></div>
<h1 id="locationline">

<span id="pagelocation"><a class="backlink" href="/nutch/FrontPage?action=fullsearch&amp;value=linkto%3A%22FrontPage%22&amp;context=180" rel="nofollow" title="Click to do a full-text search for this title">FrontPage</a></span>
</h1>


<ul id="navibar">
<li class="wikilink current"><a href="/nutch/FrontPage">FrontPage</a></li><li class="wikilink"><a href="/nutch/RecentChanges">RecentChanges</a></li><li class="wikilink"><a href="/nutch/FindPage">FindPage</a></li><li class="wikilink"><a href="/nutch/HelpContents">HelpContents</a></li>
</ul>

<div id="pageline"><hr style="display:none;"></div>

<ul class="editbar"><li><span class="disabled">Immutable Page</span></li><li class="toggleCommentsButton" style="display:none;"><a href="#" class="nbcomment" onClick="toggleComments();return false;">Comments</a></li><li><a class="nbinfo" href="/nutch/FrontPage?action=info" rel="nofollow">Info</a></li><li><a class="nbattachments" href="/nutch/FrontPage?action=AttachFile" rel="nofollow">Attachments</a></li><li>
<form class="actionsmenu" method="GET" action="/nutch/FrontPage">
<div>
    <label>More Actions:</label>
    <select name="action"
        onchange="if ((this.selectedIndex != 0) &&
                      (this.options[this.selectedIndex].disabled == false)) {
                this.form.submit();
            }
            this.selectedIndex = 0;">
        <option value="raw">Raw Text</option>
<option value="print">Print View</option>
<option value="RenderAsDocbook">Render as Docbook</option>
<option value="refresh">Delete Cache</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="SpellCheck">Check Spelling</option>
<option value="LikePages">Like Pages</option>
<option value="LocalSiteMap">Local Site Map</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="RenamePage" disabled class="disabled">Rename Page</option>
<option value="CopyPage">Copy Page</option>
<option value="DeletePage" disabled class="disabled">Delete Page</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="MyPages">My Pages</option>
<option value="show" disabled class="disabled">Subscribe User</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="show" disabled class="disabled">Remove Spam</option>
<option value="show" disabled class="disabled">Revert to this revision</option>
<option value="PackagePages">Package Pages</option>
<option value="SyncPages">Sync Pages</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="Load">Load</option>
<option value="Save">Save</option>
<option value="SlideShow">SlideShow</option>
    </select>
    <input type="submit" value="Do">
    
</div>
<script type="text/javascript">
<!--// Init menu
actionsMenuInit('More Actions:');
//-->
</script>
</form>
</li></ul>

</div>

<div id="page" lang="en" dir="ltr">
<div dir="ltr" id="content" lang="en"><span class="anchor" id="top"></span>
<span class="anchor" id="line-1"></span><p class="line867">
<h1 id="Welcome_to_the_Apache_Nutch_Wiki">Welcome to the Apache Nutch Wiki</h1>
<span class="anchor" id="line-2"></span><p class="line867"><img alt="nutch_logo_medium.gif" class="attachment" src="/nutch/FrontPage?action=AttachFile&amp;do=get&amp;target=nutch_logo_medium.gif" title="nutch_logo_medium.gif" /> <span class="anchor" id="line-3"></span><span class="anchor" id="line-4"></span><p class="line862">Please contribute your knowledge about Nutch here! <div class="table-of-contents"><p class="table-of-contents-heading">Contents<ol><li>
<a href="#Welcome_to_the_Apache_Nutch_Wiki">Welcome to the Apache Nutch Wiki</a><ol><li>
<a href="#Nutch_Version_Administration">Nutch Version Administration</a><ol><li>
<a href="#Tutorials">Tutorials</a><ol><li>
<a href="#Nutch_1.X_tutorial.28s.29">Nutch 1.X tutorial(s)</a></li><li>
<a href="#Nutch_2.X_tutorial.28s.29">Nutch 2.X tutorial(s)</a></li><li>
<a href="#Other_Tutorial.28s.29">Other Tutorial(s)</a></li></ol></li><li>
<a href="#Configuration">Configuration</a></li></ol></li><li>
<a href="#General_Information">General Information</a></li><li>
<a href="#Nutch_Development">Nutch Development</a></li><li>
<a href="#Nutch_2.x">Nutch 2.x</a></li><li>
<a href="#Pre_Nutch_1.3_and_Archive">Pre Nutch 1.3 and Archive</a></li><li>
<a href="#How_to_edit_this_Wiki">How to edit this Wiki</a></li></ol></li></ol></div> <span class="anchor" id="line-5"></span><span class="anchor" id="line-6"></span><p class="line867">
<h2 id="Nutch_Version_Administration">Nutch Version Administration</h2>
<span class="anchor" id="line-7"></span><ul><li><p class="line891"><a href="/nutch/DownloadingNutch">DownloadingNutch</a> <span class="anchor" id="line-8"></span></li><li><p class="line862">Current <a href="/nutch/CommandLineOptions">CommandLineOptions</a>: Command line options for 1.X and 2.X  <span class="anchor" id="line-9"></span></li><li><p class="line891"><a class="http" href="http://nutch.apache.org/apidocs-1.6/index.html">JavaDocs</a> -- The JavaDocs for the most recent Nutch-1.X release. <span class="anchor" id="line-10"></span></li><li><p class="line891"><a class="http" href="http://nutch.apache.org/apidocs-2.1/index.html">JavaDocs</a> -- The JavaDocs for the most recent Nutch-2.X release. <span class="anchor" id="line-11"></span><span class="anchor" id="line-12"></span></li></ul><p class="line867">
<h3 id="Tutorials">Tutorials</h3>
<span class="anchor" id="line-13"></span><span class="anchor" id="line-14"></span><p class="line867">
<h4 id="Nutch_1.X_tutorial.28s.29">Nutch 1.X tutorial(s)</h4>
<span class="anchor" id="line-15"></span><ul><li><p class="line891"><a href="/nutch/NutchTutorial">NutchTutorial</a> - How to configure Nutch to crawl in local mode and post to Apache Solr for search/index. <span class="anchor" id="line-16"></span><span class="anchor" id="line-17"></span></li></ul><p class="line867">
<h4 id="Nutch_2.X_tutorial.28s.29">Nutch 2.X tutorial(s)</h4>
<span class="anchor" id="line-18"></span><ul><li><p class="line891"><a href="/nutch/Nutch2Tutorial">Nutch2Tutorial</a> -- How to get Nutch 2.X to use HBase as persistence layer for Gora   <span class="anchor" id="line-19"></span></li><li><p class="line891"><a class="http" href="http://nlp.solutions.asia/?p=180">Setting up Nutch 2.0 with MySQL to handle UTF-8</a> - A step-by-step tutorial <span class="anchor" id="line-20"></span></li><li><p class="line891"><a class="http" href="http://www.covert.io/post/18414889381/accumulo-nutch-and-gora">Accumulo, Nutch, and Gora</a> - A step-by-step tutorial <span class="anchor" id="line-21"></span></li><li><p class="line891"><a href="/nutch/Nutch2Cassandra">Setting up Nutch 2.x with Cassandra</a> - How to setup and run Nutch 2.x using Cassandra as storage. <span class="anchor" id="line-22"></span><span class="anchor" id="line-23"></span></li></ul><p class="line867">
<h4 id="Other_Tutorial.28s.29">Other Tutorial(s)</h4>
<span class="anchor" id="line-24"></span><ul><li><p class="line891"><a class="http" href="http://hadoop.apache.org/common/docs/stable/">Hadoop Tutorial</a> Nutch being based Hadoop, it helps to have a better understanding of Hadoop. <span class="anchor" id="line-25"></span></li><li><p class="line891"><a href="/nutch/NutchHadoopSingleNodeTutorial">Running Nutch in (pseudo) distributed mode</a> - How to setup and run Nutch in Hadoop pseudo-distributed mode. <span class="anchor" id="line-26"></span></li><li><p class="line891"><a href="/nutch/RunNutchInEclipse">RunNutchInEclipse</a> - How to configure, build, crawl and debug Nutch within Eclipse <span class="anchor" id="line-27"></span></li><li><p class="line891"><a href="/nutch/IntranetDocumentSearch">Intranet Document Search</a> - Index and search Microsoft Office, PDF etc. documents in a file system hierarchy with a Solr backend. <span class="anchor" id="line-28"></span></li><li><p class="line891"><a class="http" href="http://pascaldimassimo.com/2010/06/11/how-to-re-crawl-with-nutch/">Recrawling with Nutch</a> - How to re-crawl with Nutch.  <span class="anchor" id="line-29"></span></li><li><p class="line891"><a class="https" href="https://github.com/evolvingweb/ajax-solr/wiki/Tutorial%3A-Nutch">Ajax-Solr Tutorial: Nutch</a> - Quick and easy guide to getting a nice UI on top of your Nutch crawl data.  <span class="anchor" id="line-30"></span><span class="anchor" id="line-31"></span><span class="anchor" id="line-32"></span></li></ul><p class="line867">
<h3 id="Configuration">Configuration</h3>
<span class="anchor" id="line-33"></span><ul><li><p class="line891"><a href="/nutch/OverviewDeploymentConfigs">OverviewDeploymentConfigs</a> <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :This full page requires a complete update to reflect recent Nutch releases: <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> <span class="anchor" id="line-34"></span></li><li><p class="line891"><a href="/nutch/NutchConfigurationFiles">NutchConfigurationFiles</a>: An overview from Nutch developers. <span class="anchor" id="line-35"></span></li><li><p class="line891"><a href="/nutch/NutchPropertiesCompleteList">NutchPropertiesCompleteList</a>: A fine grained account of all Nutch property configuration. <span class="anchor" id="line-36"></span></li><li><p class="line891"><a href="/nutch/HttpAuthenticationSchemes">HttpAuthenticationSchemes</a> - How to enable Nutch to authenticate itself using NTLM, Basic or Digest authentication schemes. <span class="anchor" id="line-37"></span></li><li><p class="line891"><a href="/nutch/NonDefaultIntranetCrawlingOptions">NonDefaultIntranetCrawlingOptions</a> - Desirable options to add to your Nutch intranet crawling configuration. <span class="anchor" id="line-38"></span></li><li><p class="line891"><a href="/nutch/OptimizingCrawls">OptimizingCrawls</a> - How to optimise your crawling/fetching speed with Nutch. <span class="anchor" id="line-39"></span></li><li><p class="line891"><a href="/nutch/ErrorMessages">ErrorMessages</a> -- What they mean and suggestions for getting rid of them. <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :This requires extensive updating to reflect recent Nutch releases. In addition the legacy indexing and searching material should be archived. <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> <span class="anchor" id="line-40"></span></li><li><p class="line891"><a href="/nutch/SetupProxyForNutch">SetupProxyForNutch</a> - using Tinyproxy on Ubuntu <span class="anchor" id="line-41"></span></li><li><p class="line891"><a href="/nutch/IndexStructure">IndexStructure</a> <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :This page needs a slight update to provide more information on plugins and the data they send to Solr for indexing: <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> <span class="anchor" id="line-42"></span><span class="anchor" id="line-43"></span></li></ul><p class="line867">
<h2 id="General_Information">General Information</h2>
<span class="anchor" id="line-44"></span><ul><li><p class="line891"><a class="http" href="http://nutch.apache.org">Nutch Website</a> <span class="anchor" id="line-45"></span></li><li><p class="line891"><a href="/nutch/Features">Features</a> <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :TODO:This needs to be completely overhauled to reflect recent Nutch features. <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> <span class="anchor" id="line-46"></span></li><li><p class="line862">Current <a href="/nutch/NutchGotchas">Nutch Gotchas</a> <span class="anchor" id="line-47"></span></li><li><p class="line891"><a href="/nutch/PublicServers">PublicServers</a> running Nutch <span class="anchor" id="line-48"></span></li><li><p class="line891"><a href="/nutch/Presentations">Presentations</a> on Nutch <span class="anchor" id="line-49"></span></li><li><p class="line862">Press <a href="/nutch/Articles">Articles</a> <span class="anchor" id="line-50"></span></li><li><p class="line891"><a href="/nutch/Evaluations">Evaluations</a> of Search Quality <span class="anchor" id="line-51"></span></li><li><p class="line862">Commercial <a href="/nutch/Support">Support</a> &amp; developers for hire <span class="anchor" id="line-52"></span></li><li><p class="line891"><a href="/nutch/Mailing">Mailing</a> Lists <span class="anchor" id="line-53"></span></li><li><p class="line891"><a href="/nutch/AcademicArticles">AcademicArticles</a> that deal with Nutch <span class="anchor" id="line-54"></span></li><li><p class="line891"><a href="/nutch/FAQ">FAQ</a> <span class="anchor" id="line-55"></span></li><li><p class="line891"><a href="/nutch/HardwareRequirements">HardwareRequirements</a> <span class="anchor" id="line-56"></span></li><li><p class="line891"><a href="/nutch/NutchResources">NutchResources</a> <span class="anchor" id="line-57"></span><span class="anchor" id="line-58"></span></li></ul><p class="line867">
<h2 id="Nutch_Development">Nutch Development</h2>
<span class="anchor" id="line-59"></span><ul><li><p class="line891"><a href="/nutch/Becoming_A_Nutch_Developer">Becoming a Nutch Developer</a> - Start developing and contributing to Nutch. <span class="anchor" id="line-60"></span></li><li><p class="line891"><a href="/nutch/PluginCentral">PluginCentral</a> -- How to write your own plugins and use other people's. <span class="anchor" id="line-61"></span></li><li><p class="line891"><a href="/nutch/InternalDocumentation">InternalDocumentation</a> -- How Nutch works. <span class="anchor" id="line-62"></span></li><li><p class="line891"><a class="http" href="http://nutch.apache.org/version_control.html">Nutch Version Control</a> <span class="anchor" id="line-63"></span></li><li><p class="line891"><a href="/nutch/FixingOpicScoring">FixingOpicScoring</a> - <em>In planning</em>. <span class="anchor" id="line-64"></span></li><li><p class="line891"><a href="/nutch/HowToContribute">HowToContribute</a> <span class="anchor" id="line-65"></span></li><li><p class="line891"><a href="/nutch/TaskList">TaskList</a> -- Tasks for Nutch developers. <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :Severe update required: <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> <span class="anchor" id="line-66"></span></li><li><p class="line891"><a href="/nutch/Committer%27s_Rules">Committer's_Rules</a> -- Committers should follow these guidelines when deciding, which branch to use for committing the patches and when to commit. <span class="anchor" id="line-67"></span></li><li><p class="line891"><a href="/nutch/Release_HOWTO">Release_HOWTO</a> <span class="anchor" id="line-68"></span></li><li><p class="line891"><a href="/nutch/Website_Update_HOWTO">Website_Update_HOWTO</a> <span class="anchor" id="line-69"></span></li><li><p class="line891"><a href="/nutch/Image_Search_Design">Image_Search_Design</a> <span class="anchor" id="line-70"></span></li><li><p class="line891"><a href="/nutch/StrategicGoals">StrategicGoals</a> <span class="anchor" id="line-71"></span></li><li><p class="line891"><a href="/nutch/Getting_Started">Getting_Started</a> <span class="anchor" id="line-72"></span></li><li><p class="line891"><a href="/nutch/NutchMeetUps">NutchMeetUps</a> - Records of previous Nutch community meetup, hackathons, barcamps etc. <span class="anchor" id="line-73"></span></li><li><p class="line891"><a href="/nutch/NutchMavenSupport">Using Nutch as a Maven dependency</a> <span class="anchor" id="line-74"></span><span class="anchor" id="line-75"></span></li></ul><p class="line867">
<h2 id="Nutch_2.x">Nutch 2.x</h2>
<span class="anchor" id="line-76"></span><ul><li><p class="line891"><a href="/nutch/Nutch2Crawling">Nutch2Crawling</a> - A description of the crawling jobs and field to database mappings. <span class="anchor" id="line-77"></span></li><li><p class="line891"><a href="/nutch/Nutch2Architecture">Nutch2Architecture</a> - A high level overview of the new architecture and design <span class="anchor" id="line-78"></span></li><li><p class="line891"><a href="/nutch/Nutch2Roadmap">Nutch2Roadmap</a> -- Discussions on the architecture and features of Nutch 2.0 <span class="anchor" id="line-79"></span></li><li><p class="line891"><a href="/nutch/NewScoring">NewScoring</a> -- New stable pagerank like webgraph and link-analysis jobs. <span class="anchor" id="line-80"></span></li><li><p class="line891"><a href="/nutch/NewScoringIndexingExample">NewScoringIndexingExample</a> -- Two full fetch cycles of commands using new scoring and indexing systems. <span class="anchor" id="line-81"></span></li><li><p class="line891"><a class="http" href="http://techvineyard.blogspot.com/2010/12/build-nutch-20.html">Build Nutch 2.0 in Eclipse</a> -- How to setup your IDE environment comfortably. <span class="anchor" id="line-82"></span></li><li><p class="line891"><a href="/nutch/ErrorMessagesInNutch2">ErrorMessagesInNutch2</a> -- What they mean and suggestions for getting rid of them. <span class="anchor" id="line-83"></span></li><li><p class="line891"><a href="/nutch/NutchConfigurationFiles-2.x">NutchConfigurationFiles-2.x</a> -- Configuration files that are specific to Nutch-2.x <span class="anchor" id="line-84"></span></li><li><p class="line891"><a class="http" href="http:///nlp.solutions.asia/?p=232">Understanding the columns/fields in Nutch 2.0 Webpage -  Detailed article</a> <span class="anchor" id="line-85"></span></li><li><p class="line891"><a href="/nutch/WorkingWithGoraSnapshots">WorkingWithGoraSnapshots</a> - A step by step guide to working with Gora development code within your Nutch 2.x deployment <span class="anchor" id="line-86"></span><span class="anchor" id="line-87"></span></li></ul><p class="line867">
<h2 id="Pre_Nutch_1.3_and_Archive">Pre Nutch 1.3 and Archive</h2>
<span class="anchor" id="line-88"></span><ul><li><p class="line891"><a href="/nutch/Archive%20and%20Legacy">Archive and Legacy</a> <span class="anchor" id="line-89"></span><span class="anchor" id="line-90"></span></li></ul><p class="line867">
<h2 id="How_to_edit_this_Wiki">How to edit this Wiki</h2>
<span class="anchor" id="line-91"></span><p class="line874">This Wiki is a collaborative site, anyone can contribute and share: <span class="anchor" id="line-92"></span><span class="anchor" id="line-93"></span><ul><li>Create an account by clicking the "Login" link at the top of any page, and picking a username and password. <span class="anchor" id="line-94"></span></li><li><p class="line862">Edit any page by pressing <strong>Edit</strong> at the top or the bottom of the page <span class="anchor" id="line-95"></span><span class="anchor" id="line-96"></span></li></ul><p class="line874">There are some conventions used on the Nutch wiki: <span class="anchor" id="line-97"></span><span class="anchor" id="line-98"></span><ul><li><p class="line891"><img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" /> :TODO: <img alt="/!\" height="16" src="/wiki/modernized/img/alert.png" title="/!\" width="16" />  (<tt class="backtick">/!\&nbsp;:TODO:&nbsp;/!\</tt> ) is used to denote sections that definitely need to be cleaned up. <span class="anchor" id="line-99"></span><span class="anchor" id="line-100"></span></li></ul><p class="line874">Some general info on using this Wiki Software: <span class="anchor" id="line-101"></span><span class="anchor" id="line-102"></span><ul><li><p class="line862">Create a link to another page with joined capitalized words (like <a href="/nutch/WikiSandBox">WikiSandBox</a>) or with <tt>["quoted&nbsp;words&nbsp;in&nbsp;brackets"]</tt> <span class="anchor" id="line-103"></span></li><li><p class="line862">See <a href="/nutch/HelpForBeginners">HelpForBeginners</a> to get you going, <a href="/nutch/HelpContents">HelpContents</a> for all help pages. <span class="anchor" id="line-104"></span></li><li><p class="line891"><a href="/nutch/HelpOnMoinWikiSyntax">HelpOnMoinWikiSyntax</a>: quick access to wiki syntax <span class="anchor" id="line-105"></span></li></ul><span class="anchor" id="bottom"></span></div><p id="pageinfo" class="info" lang="en" dir="ltr">FrontPage  (last edited 2014-01-22 11:50:23 by <span title="TejasPatil @ 106.79.168.188[106.79.168.188]"><a class="nonexistent" href="/nutch/TejasPatil" title="TejasPatil @ 106.79.168.188[106.79.168.188]">TejasPatil</a></span>)</p>

<div id="pagebottom"></div>
</div>


<div id="footer">
<ul class="editbar"><li><span class="disabled">Immutable Page</span></li><li class="toggleCommentsButton" style="display:none;"><a href="#" class="nbcomment" onClick="toggleComments();return false;">Comments</a></li><li><a class="nbinfo" href="/nutch/FrontPage?action=info" rel="nofollow">Info</a></li><li><a class="nbattachments" href="/nutch/FrontPage?action=AttachFile" rel="nofollow">Attachments</a></li><li>
<form class="actionsmenu" method="GET" action="/nutch/FrontPage">
<div>
    <label>More Actions:</label>
    <select name="action"
        onchange="if ((this.selectedIndex != 0) &&
                      (this.options[this.selectedIndex].disabled == false)) {
                this.form.submit();
            }
            this.selectedIndex = 0;">
        <option value="raw">Raw Text</option>
<option value="print">Print View</option>
<option value="RenderAsDocbook">Render as Docbook</option>
<option value="refresh">Delete Cache</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="SpellCheck">Check Spelling</option>
<option value="LikePages">Like Pages</option>
<option value="LocalSiteMap">Local Site Map</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="RenamePage" disabled class="disabled">Rename Page</option>
<option value="CopyPage">Copy Page</option>
<option value="DeletePage" disabled class="disabled">Delete Page</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="MyPages">My Pages</option>
<option value="show" disabled class="disabled">Subscribe User</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="show" disabled class="disabled">Remove Spam</option>
<option value="show" disabled class="disabled">Revert to this revision</option>
<option value="PackagePages">Package Pages</option>
<option value="SyncPages">Sync Pages</option>
<option value="show" disabled class="disabled">------------------------</option>
<option value="Load">Load</option>
<option value="Save">Save</option>
<option value="SlideShow">SlideShow</option>
    </select>
    <input type="submit" value="Do">
    
</div>
<script type="text/javascript">
<!--// Init menu
actionsMenuInit('More Actions:');
//-->
</script>
</form>
</li></ul>

<ul id="credits">
<li><a href="http://moinmo.in/" title="This site uses the MoinMoin Wiki software.">MoinMoin Powered</a></li><li><a href="http://moinmo.in/Python" title="MoinMoin is written in Python.">Python Powered</a></li><li><a href="http://moinmo.in/GPL" title="MoinMoin is GPL licensed.">GPL licensed</a></li><li><a href="http://validator.w3.org/check?uri=referer" title="Click here to validate this page.">Valid HTML 4.01</a></li>
</ul>


</div>
</body>
</html>




```
