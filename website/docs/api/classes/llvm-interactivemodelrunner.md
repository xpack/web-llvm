---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interactivemodelrunner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InteractiveModelRunner` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> that asks for advice from an external agent, or host. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InteractiveModelRunner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">llvm/Analysis/InteractiveModelRunner.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> interface: abstraction of a mechanism for evaluating a ML model. <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ed5b95e51fbe7344411033a06329be">InteractiveModelRunner</a> (LLVMContext &amp;Ctx, const std::vector&lt; TensorSpec &gt; &amp;Inputs, const TensorSpec &amp;Advice, StringRef OutboundName, StringRef InboundName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9191164e6c15ad4eabdd4d3d049a62c2">~InteractiveModelRunner</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd24bb7114ceab6169ea9569b8037370">switchContext</a> (StringRef Name) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1fec5fa04e9224027895cf709b69b1">evaluateUntyped</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f7bdb231af99457c4a9f01a544d010">Inbound</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf66f78375475e6bedee1fba139f10b8">InputSpecs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539d1071762f2903037b021d6b743bb9">OutputSpec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad06895e76dfcaf4708f81f3bcbc253">OutEC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83b88a16d5cf0c53b250725dde17847">InEC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac433e48e0c9491073030903ca3c3cc6b">OutputBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/logger">Logger</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46699200a1d39264d11b26dd4f08fe37">Log</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0a30b81625e4b11fa9614a896aa645">classof</a> (const MLModelRunner *R)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> that asks for advice from an external agent, or host.</p>


<p>It uses 2 files - ideally named pipes - one to send data to that agent, and one to receive advice. The data exchange uses the training logger (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/traininglogger-h">Utils/TrainingLogger.h</a>) format. Specifically, the compiler will send the log header, set the context, and send observations; the host is expected to reply with a tensor value after each observation as a binary buffer that's conforming to the shape of the advice. Interleaved, the data closely resembles the training log for a log where we don't capture the reward signal.</p>


<p>Note that the correctness of the received data is the responsibility of the host. In particular, if insufficient data were sent, the compiler will block when waiting for an advice.</p>


<p>Note that the host can either open the pipes RW, or open first the pipe to the compiler - i.e. the "Inbound" - and then the "Outbound", to avoid deadlock. This is because the compiler first tries to open the inbound (which will hang until there's a writer on the other end).</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InteractiveModelRunner() {#a82ed5b95e51fbe7344411033a06329be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InteractiveModelRunner::InteractiveModelRunner (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a> &gt; &amp; Inputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a> &amp; Advice, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OutboundName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InboundName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/interactivemodelrunner-cpp">InteractiveModelRunner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#afa197695caf1d92f3efeddd1156d9cde">llvm::MLModelRunner::Ctx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a81819d92a6045c9191f144ca86044b35a24b9b8c0634a40138e76b2fb86894698">llvm::MLModelRunner::Interactive</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#ad3a2236255bf0a1c90006508a28a21fd">llvm::MLModelRunner::MLModelRunner</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a8b505a9ebc9388db882b94a334daa84c">llvm::MLModelRunner::setUpBufferForTensor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InteractiveModelRunner() {#a9191164e6c15ad4eabdd4d3d049a62c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InteractiveModelRunner::~InteractiveModelRunner ()</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/interactivemodelrunner-cpp">InteractiveModelRunner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a43548658b3d92c080577422f81f38038">llvm::sys::fs::closeFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac90e775833cd4fd0da26c96bfa8f2f06">llvm::sys::fs::convertFDToNativeFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### switchContext() {#acd24bb7114ceab6169ea9569b8037370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InteractiveModelRunner::switchContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateUntyped() {#aec1fec5fa04e9224027895cf709b69b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * InteractiveModelRunner::evaluateUntyped ()</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/interactivemodelrunner-cpp">InteractiveModelRunner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Inbound {#a63f7bdb231af99457c4a9f01a544d010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InteractiveModelRunner::Inbound = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### InEC {#ad83b88a16d5cf0c53b250725dde17847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::InteractiveModelRunner::InEC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### InputSpecs {#abf66f78375475e6bedee1fba139f10b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt;TensorSpec&gt; llvm::InteractiveModelRunner::InputSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### Log {#a46699200a1d39264d11b26dd4f08fe37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Logger&gt; llvm::InteractiveModelRunner::Log</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### OutEC {#a0ad06895e76dfcaf4708f81f3bcbc253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::InteractiveModelRunner::OutEC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### OutputBuffer {#ac433e48e0c9491073030903ca3c3cc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;char&gt; llvm::InteractiveModelRunner::OutputBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

### OutputSpec {#a539d1071762f2903037b021d6b743bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TensorSpec llvm::InteractiveModelRunner::OutputSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a2c0a30b81625e4b11fa9614a896aa645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InteractiveModelRunner::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a81819d92a6045c9191f144ca86044b35a24b9b8c0634a40138e76b2fb86894698">llvm::MLModelRunner::Interactive</a> and <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#ad3a2236255bf0a1c90006508a28a21fd">llvm::MLModelRunner::MLModelRunner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">InteractiveModelRunner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/interactivemodelrunner-cpp">InteractiveModelRunner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
