---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-statistic-cpp-/statisticinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StatisticInfo` Class Reference

<p>This class is used in a <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> so that it is created on demand (when the first statistic is bumped) and destroyed only when llvm_shutdown is called. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{Statistic.cpp}::StatisticInfo { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa092df693297372d76beda948eed904f">const_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd0ec7b5a3c020132c82736b694e6cb">llvm::PrintStatistics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914ae87992fc63f360285419b0031d9b">llvm::PrintStatistics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70edbe083a3dd7b0ad557466afb69200">llvm::PrintStatisticsJSON</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ae42d0878ba114fe7843b2129b9611">StatisticInfo</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91198341d265a83ba2657a4eb140d0dc">~StatisticInfo</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad90420121bd6daed43d86479000c2b">addStatistic</a> (TrackingStatistic *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa092df693297372d76beda948eed904f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3735bd99f4c0e2f305419c9c038434">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa092df693297372d76beda948eed904f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891dbb2b3761aa1053445d8e906169ff">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aa092df693297372d76beda948eed904f">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706e115037bb86960cae5c9ec7e791f4">statistics</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a9ccf524624d58bb8f87b75dcb2b34">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7be79a865df519110558cf476146bd2">sort</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort statistics by debugtype,name,description. <a href="#ab7be79a865df519110558cf476146bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae177184c3e8caa2aa676731ef92fd781">Stats</a></td>
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

<p>This class is used in a <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> so that it is created on demand (when the first statistic is bumped) and destroyed only when llvm_shutdown is called.</p>


<p>We print statistics from the destructor. This class is also used to look up statistic values from applications that use LLVM.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aa092df693297372d76beda948eed904f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{Statistic.cpp}::StatisticInfo::const_iterator =  std::vector&lt;TrackingStatistic *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### llvm::PrintStatistics {#adcd0ec7b5a3c020132c82736b694e6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

### llvm::PrintStatistics {#a914ae87992fc63f360285419b0031d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

### llvm::PrintStatisticsJSON {#a70edbe083a3dd7b0ad557466afb69200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StatisticInfo() {#a15ae42d0878ba114fe7843b2129b9611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatisticInfo::StatisticInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/timergroup/#af7e26e04ebc4659b165821aa390316a7">llvm::TimerGroup::constructForStatistics</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~StatisticInfo() {#a91198341d265a83ba2657a4eb140d0dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatisticInfo::~StatisticInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a38906af8cc37ba9ddf2260cf1e2b0483">EnableStats</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a53f79cf8812ccb9a9d038c66e138176d">PrintOnExit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addStatistic() {#a6ad90420121bd6daed43d86479000c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{Statistic.cpp}::StatisticInfo::addStatistic (<a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> * S)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

### begin() {#a4f3735bd99f4c0e2f305419c9c038434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{Statistic.cpp}::StatisticInfo::begin ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="#a706e115037bb86960cae5c9ec7e791f4">statistics</a>.</p>

</div>
</div>

### end() {#a891dbb2b3761aa1053445d8e906169ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{Statistic.cpp}::StatisticInfo::end ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="#a706e115037bb86960cae5c9ec7e791f4">statistics</a>.</p>

</div>
</div>

### reset() {#a66a9ccf524624d58bb8f87b75dcb2b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StatisticInfo::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#ac984e1f297b2dac8cbf7c4cf8777e4ea">StatLock</a>.</p>

</div>
</div>

### statistics() {#a706e115037bb86960cae5c9ec7e791f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; anonymous{Statistic.cpp}::StatisticInfo::statistics ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>References <a href="#a4f3735bd99f4c0e2f305419c9c038434">begin</a> and <a href="#a891dbb2b3761aa1053445d8e906169ff">end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### sort() {#ab7be79a865df519110558cf476146bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StatisticInfo::sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sort statistics by debugtype,name,description.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Stats {#ae177184c3e8caa2aa676731ef92fd781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TrackingStatistic *&gt; anonymous{Statistic.cpp}::StatisticInfo::Stats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
