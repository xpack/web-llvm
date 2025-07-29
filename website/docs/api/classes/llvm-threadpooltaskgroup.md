---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/threadpooltaskgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThreadPoolTaskGroup` Class

<p>A group of tasks to be run on a thread pool. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ThreadPoolTaskGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd12a64f20a69db19551fc17380766ea">ThreadPoolTaskGroup</a> (ThreadPoolInterface &amp;Pool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ThreadPool argument is the thread pool to forward calls to. <a href="#afd12a64f20a69db19551fc17380766ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb68d4d5c87b07400ebf71f489ddd4d3">~ThreadPoolTaskGroup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking destructor: will wait for all the tasks in the group to complete by calling ThreadPool::wait(). <a href="#abb68d4d5c87b07400ebf71f489ddd4d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Function, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a5b93ca9163a7977cc2114eacb65fb0">async</a> (Function &amp;&amp;F, Args &amp;&amp;...ArgList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls ThreadPool::async() for this group. <a href="#a4a5b93ca9163a7977cc2114eacb65fb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f164d97bb4385520807d75a0c0db5a">wait</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls ThreadPool::wait() for this group. <a href="#ab4f164d97bb4385520807d75a0c0db5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface">ThreadPoolInterface</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57cc417616ff63dc94213d23ad9d6528">Pool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A group of tasks to be run on a thread pool.</p>


<p>Thread pool tasks in different groups can run on the same threadpool but can be waited for separately. It is even possible for tasks of one group to submit and wait for tasks of another group, as long as this does not form a loop.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreadPoolTaskGroup() {#afd12a64f20a69db19551fc17380766ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadPoolTaskGroup::ThreadPoolTaskGroup (<a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface">ThreadPoolInterface</a> &amp; Pool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ThreadPool argument is the thread pool to forward calls to.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ThreadPoolTaskGroup() {#abb68d4d5c87b07400ebf71f489ddd4d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadPoolTaskGroup::~ThreadPoolTaskGroup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking destructor: will wait for all the tasks in the group to complete by calling ThreadPool::wait().</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Reference <a href="#ab4f164d97bb4385520807d75a0c0db5a">wait</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### async() {#a4a5b93ca9163a7977cc2114eacb65fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Function, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::ThreadPoolTaskGroup::async (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;&amp; F, Args &amp;&amp;... ArgList)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls ThreadPool::async() for this group.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### wait() {#ab4f164d97bb4385520807d75a0c0db5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThreadPoolTaskGroup::wait ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls ThreadPool::wait() for this group.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Referenced by <a href="#abb68d4d5c87b07400ebf71f489ddd4d3">~ThreadPoolTaskGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Pool {#a57cc417616ff63dc94213d23ad9d6528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPoolInterface&amp; llvm::ThreadPoolTaskGroup::Pool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
