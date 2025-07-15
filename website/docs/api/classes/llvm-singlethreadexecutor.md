---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/singlethreadexecutor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SingleThreadExecutor` Class Reference

<p>A non-threaded implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SingleThreadExecutor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface">ThreadPoolInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This defines the abstract base interface for a ThreadPool allowing asynchronous parallel execution on a defined number of threads. <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0e760e0380aa0023a27372d5ffd4dc">SingleThreadExecutor</a> (ThreadPoolStrategy ignored={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a non-threaded pool, ignoring using the hardware strategy. <a href="#a3a0e760e0380aa0023a27372d5ffd4dc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a551b6b62422a531ea1b88f57071afca1">~SingleThreadExecutor</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking destructor: the pool will first execute the pending tasks. <a href="#a551b6b62422a531ea1b88f57071afca1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9fc38bb7d9ff3f944e25971330cb42">wait</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking wait for all the tasks to execute first. <a href="#a4a9fc38bb7d9ff3f944e25971330cb42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49af26efe3b94237c38fc28a166f3386">wait</a> (ThreadPoolTaskGroup &amp;Group) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking wait for only all the tasks in the given group to complete. <a href="#a49af26efe3b94237c38fc28a166f3386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7bf90e52e4cf7b2190d1d976527b025">getMaxConcurrency</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns always 1: there is no concurrency. <a href="#ac7bf90e52e4cf7b2190d1d976527b025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a671af7165066753366fd0dcde0d560c9">getThreadCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f1263cc6c0e4c711a1936736d61db6">isWorkerThread</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the current thread is a worker thread of this thread pool. <a href="#ac4f1263cc6c0e4c711a1936736d61db6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acfa809163ab2fcd803aec68d59a4ce">asyncEnqueue</a> (std::function&lt; void()&gt; Task, ThreadPoolTaskGroup *Group) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asynchronous submission of a task to the pool. <a href="#a9acfa809163ab2fcd803aec68d59a4ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; std::pair&lt; std::function&lt; void()&gt;, <a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9adf8bf7fd2be7f9ba55fcd1dd68c38">Tasks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tasks waiting for execution in the pool. <a href="#af9adf8bf7fd2be7f9ba55fcd1dd68c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A non-threaded implementation.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SingleThreadExecutor() {#a3a0e760e0380aa0023a27372d5ffd4dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SingleThreadExecutor::SingleThreadExecutor (<a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ignored={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a non-threaded pool, ignoring using the hardware strategy.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy/#ac128c3b3bd0420224f86d2c385f3af99">llvm::ThreadPoolStrategy::compute_thread_count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ac93a706f78069d5f23b6084d9a1fc015">ThreadCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SingleThreadExecutor() {#a551b6b62422a531ea1b88f57071afca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SingleThreadExecutor::~SingleThreadExecutor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking destructor: the pool will first execute the pending tasks.</p>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a>.</p>


<p>Reference <a href="#a4a9fc38bb7d9ff3f944e25971330cb42">wait</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMaxConcurrency() {#ac7bf90e52e4cf7b2190d1d976527b025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SingleThreadExecutor::getMaxConcurrency ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns always 1: there is no concurrency.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

### getThreadCount() {#a671af7165066753366fd0dcde0d560c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SingleThreadExecutor::getThreadCount ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>


<p>Reference <a href="#a671af7165066753366fd0dcde0d560c9">getThreadCount</a>.</p>


<p>Referenced by <a href="#a671af7165066753366fd0dcde0d560c9">getThreadCount</a>.</p>

</div>
</div>

### isWorkerThread() {#ac4f1263cc6c0e4c711a1936736d61db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SingleThreadExecutor::isWorkerThread ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the current thread is a worker thread of this thread pool.</p>

<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### wait() {#a4a9fc38bb7d9ff3f944e25971330cb42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SingleThreadExecutor::wait ()</td>
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

<p>Blocking wait for all the tasks to execute first.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>, <a href="#a49af26efe3b94237c38fc28a166f3386">wait</a> and <a href="#a551b6b62422a531ea1b88f57071afca1">~SingleThreadExecutor</a>.</p>

</div>
</div>

### wait() {#a49af26efe3b94237c38fc28a166f3386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SingleThreadExecutor::wait (<a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> &amp; Group)</td>
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

<p>Blocking wait for only all the tasks in the given group to complete.</p>

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a>.</p>


<p>Reference <a href="#a4a9fc38bb7d9ff3f944e25971330cb42">wait</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### asyncEnqueue() {#a9acfa809163ab2fcd803aec68d59a4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SingleThreadExecutor::asyncEnqueue (std::function&lt; void()&gt; Task, <a href="/web-llvm/docs/api/classes/llvm/threadpooltaskgroup">ThreadPoolTaskGroup</a> * Group)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asynchronous submission of a task to the pool.</p>


<p>The returned future can be used to wait for the task to finish and is <em>non-blocking</em> on destruction.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Tasks {#af9adf8bf7fd2be7f9ba55fcd1dd68c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;std::pair&lt;std::function&lt;void()&gt;, ThreadPoolTaskGroup *&gt; &gt; llvm::SingleThreadExecutor::Tasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tasks waiting for execution in the pool.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">ThreadPool.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/threadpool-cpp">ThreadPool.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
