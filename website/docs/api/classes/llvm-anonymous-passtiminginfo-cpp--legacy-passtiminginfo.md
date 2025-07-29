---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-passtiminginfo-cpp-/legacy/passtiminginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PassTimingInfo` Class

<p>Provides an interface for collecting pass timing information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17077cb090ac77e5b0004e44f5d9902">PassInstanceID</a> = void *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e42cf14ce740bfe1645833326e210b1">PassTimingInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor for yet-inactive timeinfo. <a href="#a5e42cf14ce740bfe1645833326e210b1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cb7f9bbdb27835c54880131ee577c7">~PassTimingInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out timing information and release timers. <a href="#af2cb7f9bbdb27835c54880131ee577c7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401b7839a0c26aa69f47114c84e029f1">print</a> (raw_ostream *OutStream=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints out timing information and then resets the timers. <a href="#a401b7839a0c26aa69f47114c84e029f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4d99a79c2bcaaf0e30b92826156793">getPassTimer</a> (Pass *, PassInstanceID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the timer for the specified pass if it exists. <a href="#a6a4d99a79c2bcaaf0e30b92826156793">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ebc8cd2b61f1b5b4f0d52c85ea46cc">newPassTimer</a> (StringRef PassID, StringRef PassDesc)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d363610e4f9d7b23c00fc23ab217b0b">PassIDCountMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map that counts instances of passes. <a href="#a0d363610e4f9d7b23c00fc23ab217b0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#ad17077cb090ac77e5b0004e44f5d9902">PassInstanceID</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebedaa837242e1e316b80b095b16a5a5">TimingData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>timers for pass instances <a href="#aebedaa837242e1e316b80b095b16a5a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82a7c09b206ce4333ff0c26d552f692">TG</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0041e7f7389ab2feb251f54506c85a">init</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes the static <span class="doxyComputerOutput">TheTimeInfo</span> member to a non-null value when -time-passes is enabled. <a href="#a8a0041e7f7389ab2feb251f54506c85a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/anonymous-passtiminginfo-cpp-/legacy/passtiminginfo">PassTimingInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c6a7a68f950643ffed719e1d48cc91">TheTimeInfo</a></td>
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

<p>Provides an interface for collecting pass timing information.</p>


<p>It was intended to be generic but now we decided to split interfaces completely. This is now exclusively for legacy-pass-manager use.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PassInstanceID {#ad17077cb090ac77e5b0004e44f5d9902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::PassInstanceID =  void *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassTimingInfo() {#a5e42cf14ce740bfe1645833326e210b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::PassTimingInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor for yet-inactive timeinfo.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput"><a href="#a8a0041e7f7389ab2feb251f54506c85a">init()</a></span> to activate it.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<p>Reference <a href="#a5e42cf14ce740bfe1645833326e210b1">PassTimingInfo</a>.</p>


<p>Referenced by <a href="#a5e42cf14ce740bfe1645833326e210b1">PassTimingInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PassTimingInfo() {#af2cb7f9bbdb27835c54880131ee577c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::~PassTimingInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out timing information and release timers.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassTimer() {#a6a4d99a79c2bcaaf0e30b92826156793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Timer * llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::getPassTimer (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="#ad17077cb090ac77e5b0004e44f5d9902">PassInstanceID</a> Pass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the timer for the specified pass if it exists.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a8a0041e7f7389ab2feb251f54506c85a">init</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#aab174263c400ece13a7278990e102fa6">llvm::Pass::lookupPassInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-passtiminginfo-cpp-/legacy/#a177e692f5754ac7c4dd7c12ed6c1887f">llvm::anonymous{PassTimingInfo.cpp}::legacy::TimingInfoMutex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>.</p>

</div>
</div>

### print() {#a401b7839a0c26aa69f47114c84e029f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OutStream=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prints out timing information and then resets the timers.</p>


<p>By default it uses the stream created by <a href="/web-llvm/docs/api/namespaces/llvm/#a09515ea8784bdea8e0e866799bb38409">CreateInfoOutputFile()</a>.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a09515ea8784bdea8e0e866799bb38409">llvm::CreateInfoOutputFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4fcfca5f1acab67334c771877cd83a21">llvm::reportAndResetTimings</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### newPassTimer() {#a61ebc8cd2b61f1b5b4f0d52c85ea46cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Timer * llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::newPassTimer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassDesc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PassIDCountMap {#a0d363610e4f9d7b23c00fc23ab217b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::PassIDCountMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map that counts instances of passes.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

### TG {#ab82a7c09b206ce4333ff0c26d552f692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimerGroup llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::TG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

### TimingData {#aebedaa837242e1e316b80b095b16a5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PassInstanceID, std::unique_ptr&lt;Timer&gt; &gt; llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::TimingData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>timers for pass instances</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### init() {#a8a0041e7f7389ab2feb251f54506c85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::init ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes the static <span class="doxyComputerOutput">TheTimeInfo</span> member to a non-null value when -time-passes is enabled.</p>


<p>Leaves it null otherwise.</p>


<p>This method may be called multiple times.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<p>References <a href="#a45c6a7a68f950643ffed719e1d48cc91">TheTimeInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a44e2fc6ce783a1ca396d473139a0ae76">llvm::TimePassesIsEnabled</a>.</p>


<p>Referenced by <a href="#a6a4d99a79c2bcaaf0e30b92826156793">getPassTimer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### TheTimeInfo {#a45c6a7a68f950643ffed719e1d48cc91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassTimingInfo * llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::TheTimeInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="#a8a0041e7f7389ab2feb251f54506c85a">init</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fcfca5f1acab67334c771877cd83a21">llvm::reportAndResetTimings</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/passtiminginfo-cpp">PassTimingInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
