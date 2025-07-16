---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-hwaddresssanitizer-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{HWAddressSanitizer.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{HWAddressSanitizer.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer">HWAddressSanitizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instrumentation pass implementing detection of addressability bugs using tagged pointers. <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OffsetKind { <a href="#a11461998818885159244a0e5b892351f">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f09e96b3a392ac91e06cb331539b15b">optOr</a> (cl::opt&lt; T &gt; &amp;Opt, T Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0715e3604a90c77e379a370f1b133a">shouldUsePageAliases</a> (const Triple &amp;TargetTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc91847fe5e9262fde0842719b3c89d0">shouldInstrumentStack</a> (const Triple &amp;TargetTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dd73d8d6f6807d5507f969962486f4">shouldInstrumentWithCalls</a> (const Triple &amp;TargetTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261525cc8537d629e89633be521c9c82">mightUseStackSafetyAnalysis</a> (bool DisableOptimization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24599d43f44d37dfb2240a83070cbc1e">shouldUseStackSafetyAnalysis</a> (const Triple &amp;TargetTriple, bool DisableOptimization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20905ddc58638aa7a27947876a698acf">shouldDetectUseAfterScope</a> (const Triple &amp;TargetTriple)</td>
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


<div class="doxySectionDef">

## Enumerations

### OffsetKind {#a11461998818885159244a0e5b892351f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{HWAddressSanitizer.cpp}::OffsetKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kFixed<a id="a11461998818885159244a0e5b892351fa826888a09763de7e2a9f60eb85d88b24"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kGlobal<a id="a11461998818885159244a0e5b892351fa53bd3be702935175a01da237d5083537"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kIfunc<a id="a11461998818885159244a0e5b892351fa36f9171d02377aafa16e766940bc4088"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kTls<a id="a11461998818885159244a0e5b892351fa2af43525a7c435a589f490bbb2a22c99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### mightUseStackSafetyAnalysis() {#a261525cc8537d629e89633be521c9c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::mightUseStackSafetyAnalysis (bool DisableOptimization)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#ac69fc2e5e9b097e6ebeb1c4e4a34fcf3">ClUseStackSafety</a> and <a href="#a5f09e96b3a392ac91e06cb331539b15b">optOr</a>.</p>


<p>Referenced by <a href="#a24599d43f44d37dfb2240a83070cbc1e">shouldUseStackSafetyAnalysis</a>.</p>

</div>
</div>

### optOr() {#a5f09e96b3a392ac91e06cb331539b15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T anonymous{HWAddressSanitizer.cpp}::optOr (<a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; T &gt; &amp; Opt, T Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a2dc75fafb68e7669e776e19da7857cdf">llvm::cl::Option::getNumOccurrences</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#a325af16f2e5df4f00331d9c0fbe21423">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::HWAddressSanitizer</a>, <a href="#a261525cc8537d629e89633be521c9c82">mightUseStackSafetyAnalysis</a> and <a href="#a99dd73d8d6f6807d5507f969962486f4">shouldInstrumentWithCalls</a>.</p>

</div>
</div>

### shouldDetectUseAfterScope() {#a20905ddc58638aa7a27947876a698acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::shouldDetectUseAfterScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a9a4fc66faeab43a236796f382e142af4">ClUseAfterScope</a> and <a href="#abc91847fe5e9262fde0842719b3c89d0">shouldInstrumentStack</a>.</p>

</div>
</div>

### shouldInstrumentStack() {#abc91847fe5e9262fde0842719b3c89d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::shouldInstrumentStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#a579a4e0b7863b190bc30d37bf9c2eb8e">ClInstrumentStack</a> and <a href="#a6b0715e3604a90c77e379a370f1b133a">shouldUsePageAliases</a>.</p>


<p>Referenced by <a href="#a20905ddc58638aa7a27947876a698acf">shouldDetectUseAfterScope</a> and <a href="#a24599d43f44d37dfb2240a83070cbc1e">shouldUseStackSafetyAnalysis</a>.</p>

</div>
</div>

### shouldInstrumentWithCalls() {#a99dd73d8d6f6807d5507f969962486f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::shouldInstrumentWithCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#a4ad5863e6e86fc753068c9b70442fda2">ClInstrumentWithCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="#a5f09e96b3a392ac91e06cb331539b15b">optOr</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### shouldUsePageAliases() {#a6b0715e3604a90c77e379a370f1b133a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::shouldUsePageAliases (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#a8dce356709f10352aed8935a89bca152">ClUsePageAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#abc91847fe5e9262fde0842719b3c89d0">shouldInstrumentStack</a>.</p>

</div>
</div>

### shouldUseStackSafetyAnalysis() {#a24599d43f44d37dfb2240a83070cbc1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HWAddressSanitizer.cpp}::shouldUseStackSafetyAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, bool DisableOptimization)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a>.</p>


<p>References <a href="#a261525cc8537d629e89633be521c9c82">mightUseStackSafetyAnalysis</a> and <a href="#abc91847fe5e9262fde0842719b3c89d0">shouldInstrumentStack</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp">HWAddressSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
