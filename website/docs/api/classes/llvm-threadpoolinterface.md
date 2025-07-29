---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/threadpoolinterface
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThreadPoolInterface` Class

<p>This defines the abstract base interface for a ThreadPool allowing asynchronous parallel execution on a defined number of threads. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ThreadPoolInterface { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor">SingleThreadExecutor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A non-threaded implementation. <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe20bbefd5e591081ad9ac5c19eedb5a">~ThreadPoolInterface</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroying the pool will drain the pending tasks and wait. <a href="#abe20bbefd5e591081ad9ac5c19eedb5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea46b29f97f4f535c563a68a38185a4">wait</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking wait for all the threads to complete and the queue to be empty. <a href="#a0ea46b29f97f4f535c563a68a38185a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4dbcf0b0e80230eb3f28d30672eff19">wait</a> (ThreadPoolTaskGroup &amp;Group)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking wait for only all the threads in the given group to complete. <a href="#ad4dbcf0b0e80230eb3f28d30672eff19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec7a595fe1af1fa5204286641a356fc">getMaxConcurrency</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of worker this pool can eventually grow to. <a href="#a6ec7a595fe1af1fa5204286641a356fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Function, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad43d0052f680e6ac08426d8821df178d">async</a> (Function &amp;&amp;F, Args &amp;&amp;...ArgList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asynchronous submission of a task to the pool. <a href="#ad43d0052f680e6ac08426d8821df178d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Function, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c671f2f05014107ee55248f18f88dea">async</a> (ThreadPoolTaskGroup &amp;Group, Function &amp;&amp;F, Args &amp;&amp;...ArgList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload, task will be in the given task group. <a href="#a0c671f2f05014107ee55248f18f88dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7397950f434c9dff4b594c980e5d518d">async</a> (Func &amp;&amp;F) -&gt; std::shared_future&lt; decltype(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>())&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asynchronous submission of a task to the pool. <a href="#a7397950f434c9dff4b594c980e5d518d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a671aff841cc82b9c2f39b1d7272c6174">async</a> (ThreadPoolTaskGroup &amp;Group, Func &amp;&amp;F) -&gt; std::shared_future&lt; decltype(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>())&gt;</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2ed24366ea0eaa572d4273f9ff2fd6">asyncEnqueue</a> (std::function&lt; void()&gt; Task, ThreadPoolTaskGroup *Group)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual method to enqueue a task to be defined by the concrete implementation. <a href="#a7d2ed24366ea0eaa572d4273f9ff2fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ResTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace2964d9b181e3894a14807262340e1a">asyncImpl</a> (std::function&lt; ResTy()&gt; Task, ThreadPoolTaskGroup *Group) -&gt; std::shared_future&lt; ResTy &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asynchronous submission of a task to the pool. <a href="#ace2964d9b181e3894a14807262340e1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This defines the abstract base interface for a ThreadPool allowing asynchronous parallel execution on a defined number of threads.</p>


<p>It is possible to reuse one thread pool for different groups of tasks by grouping tasks using <a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a>. All tasks are processed using the same queue, but it is possible to wait only for a specific group of tasks to finish.</p>


<p>It is also possible for worker threads to submit new tasks and wait for them. Note that this may result in a deadlock in cases such as when a task (directly or indirectly) tries to wait for its own completion, or when all available threads are used up by tasks waiting for a task that has no thread left to run on (this includes waiting on the returned future). It should be generally safe to <a href="#a0ea46b29f97f4f535c563a68a38185a4">wait()</a> for a group as long as groups do not form a cycle.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~ThreadPoolInterface() {#abe20bbefd5e591081ad9ac5c19eedb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPoolInterface::~ThreadPoolInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroying the pool will drain the pending tasks and wait.</p>


<p>The current thread may participate in the execution of the pending tasks.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### async() {#ad43d0052f680e6ac08426d8821df178d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Function, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::ThreadPoolInterface::async (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;&amp; F, Args &amp;&amp;... ArgList)</td>
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

<p>Asynchronous submission of a task to the pool.</p>


<p>The returned future can be used to wait for the task to finish and is <em>non-blocking</em> on destruction.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>References <a href="#ad43d0052f680e6ac08426d8821df178d">async</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#ad43d0052f680e6ac08426d8821df178d">async</a>, <a href="#a0c671f2f05014107ee55248f18f88dea">async</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>.</p>

</div>
</div>

### async() {#a0c671f2f05014107ee55248f18f88dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Function, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::ThreadPoolInterface::async (<a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> &amp; Group, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;&amp; F, Args &amp;&amp;... ArgList)</td>
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

<p>Overload, task will be in the given task group.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>References <a href="#ad43d0052f680e6ac08426d8821df178d">async</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### async() {#a7397950f434c9dff4b594c980e5d518d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_future&lt; decltype(F())&gt; llvm::ThreadPoolInterface::async (Func &amp;&amp; F)</td>
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

<p>Asynchronous submission of a task to the pool.</p>


<p>The returned future can be used to wait for the task to finish and is <em>non-blocking</em> on destruction.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### async() {#a671aff841cc82b9c2f39b1d7272c6174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_future&lt; decltype(F())&gt; llvm::ThreadPoolInterface::async (<a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> &amp; Group, Func &amp;&amp; F)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getMaxConcurrency() {#a6ec7a595fe1af1fa5204286641a356fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::ThreadPoolInterface::getMaxConcurrency ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of worker this pool can eventually grow to.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

### wait() {#a0ea46b29f97f4f535c563a68a38185a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ThreadPoolInterface::wait ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking wait for all the threads to complete and the queue to be empty.</p>


<p>It is an error to try to add new tasks while blocking on this call. Calling <a href="#a0ea46b29f97f4f535c563a68a38185a4">wait()</a> from a task would deadlock waiting for itself.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

### wait() {#ad4dbcf0b0e80230eb3f28d30672eff19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ThreadPoolInterface::wait (<a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> &amp; Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking wait for only all the threads in the given group to complete.</p>


<p>It is possible to wait even inside a task, but waiting (directly or indirectly) on itself will deadlock. If called from a task running on a worker thread, the call may process pending tasks while waiting in order not to waste the thread.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### asyncEnqueue() {#a7d2ed24366ea0eaa572d4273f9ff2fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ThreadPoolInterface::asyncEnqueue (std::function&lt; void()&gt; Task, <a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> * Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual method to enqueue a task to be defined by the concrete implementation.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

### asyncImpl() {#ace2964d9b181e3894a14807262340e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ResTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_future&lt; ResTy &gt; llvm::ThreadPoolInterface::asyncImpl (std::function&lt; ResTy()&gt; Task, <a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> * Group)</td>
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

<p>Asynchronous submission of a task to the pool.</p>


<p>The returned future can be used to wait for the task to finish and is <em>non-blocking</em> on destruction.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

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
