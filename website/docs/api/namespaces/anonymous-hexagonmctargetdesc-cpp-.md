---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-hexagonmctargetdesc-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{HexagonMCTargetDesc.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{HexagonMCTargetDesc.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer">HexagonTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer">HexagonTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis">HexagonMCInstrAnalysis</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cbf0f1e4f9a6bf0e11f4453f89c878e">selectHexagonFS</a> (StringRef CPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; std::string, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f981e76fa8f3adc086087882cb8d783">selectCPUAndFS</a> (StringRef CPU, StringRef FS)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea799c06a81ebc7804f0dfeb8c6abb0e">MV5</a>("mv5", cl::Hidden, cl::desc("Build for Hexagon V5"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8b07639f9e4ce4803ba229d3eb3092">MV55</a>("mv55", cl::Hidden, cl::desc("Build for Hexagon V55"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bbef802364faa2709eec2f557cb1af">MV60</a>("mv60", cl::Hidden, cl::desc("Build for Hexagon V60"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd7ac7fc67ff2e7071bea916c53166f">MV62</a>("mv62", cl::Hidden, cl::desc("Build for Hexagon V62"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f962fd218d26a3e04afb9952ee42a0">MV65</a>("mv65", cl::Hidden, cl::desc("Build for Hexagon V65"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405a78336379f05386ce4535451c9260">MV66</a>("mv66", cl::Hidden, cl::desc("Build for Hexagon V66"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946ef57fa8c3ddca341ec225dbfc9d23">MV67</a>("mv67", cl::Hidden, cl::desc("Build for Hexagon V67"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a352710d4ab7db74a7d33d71b585c85">MV67T</a>("mv67t", cl::Hidden, cl::desc("Build for Hexagon V67T"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27b02a1ff6a77cde66910e6dae637d5">MV68</a>("mv68", cl::Hidden, cl::desc("Build for Hexagon V68"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad19a56208855f807f2e8548d4e9f64f0">MV69</a>("mv69", cl::Hidden, cl::desc("Build for Hexagon V69"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347bd13f61f1456fb3c8163449b460e9">MV71</a>("mv71", cl::Hidden, cl::desc("Build for Hexagon V71"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bf7aeb68398ee9123906db93ec61f5">MV71T</a>("mv71t", cl::Hidden, cl::desc("Build for Hexagon V71T"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58075072154993da11a73925cd864c1">MV73</a>("mv73", cl::Hidden, cl::desc("Build for Hexagon V73"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b028f39911c18eaebbecd94de63eaf">MV75</a>("mv75", cl::Hidden, cl::desc("Build for Hexagon V75"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8c1bc56cedd07c2a0a7433be767c11">MV79</a>("mv79", cl::Hidden, cl::desc("Build for Hexagon V79"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0772196a4e2b7dd77953b82267cb2cd1">ArchSubtargetMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca86546c248f0d993f0b5ad6982daf2">ArchSubtarget</a></td>
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

## Functions

### selectCPUAndFS() {#a0f981e76fa8f3adc086087882cb8d783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; std::string, std::string &gt; anonymous{HexagonMCTargetDesc.cpp}::selectCPUAndFS (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aa93fa22630383fe07736811e31c03f81">llvm::Hexagon_MC::selectHexagonCPU</a> and <a href="#a0cbf0f1e4f9a6bf0e11f4453f89c878e">selectHexagonFS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>.</p>

</div>
</div>

### selectHexagonFS() {#a0cbf0f1e4f9a6bf0e11f4453f89c878e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{HexagonMCTargetDesc.cpp}::selectHexagonFS (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a0ee3b68a28f3eeaacdf7b3a02478d659">EnableHexagonCabac</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ab608a076dacb8c61a1135ac0a79af239">EnableHVX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#acc5b01fc331da58853522cafa33dab7f">EnableHvxIeeeFp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8045a0a6c688b0635e3caccc408a1446">llvm::Hexagon::Generic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a31ca3cae0b846c9a58d52c656d28b5e0">llvm::Hexagon::NoArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c">llvm::Hexagon::V5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a7e2f25174ce09de028190095cc693a5e">llvm::Hexagon::V55</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd">llvm::Hexagon::V60</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264">llvm::Hexagon::V62</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb">llvm::Hexagon::V65</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d">llvm::Hexagon::V66</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7">llvm::Hexagon::V67</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">llvm::Hexagon::V68</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1">llvm::Hexagon::V69</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4">llvm::Hexagon::V71</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494">llvm::Hexagon::V73</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436ab1cab2dc211faa7bcebb331fd40454fb">llvm::Hexagon::V75</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe">llvm::Hexagon::V79</a>.</p>


<p>Referenced by <a href="#a0f981e76fa8f3adc086087882cb8d783">selectCPUAndFS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ArchSubtarget {#a2ca86546c248f0d993f0b5ad6982daf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string, std::unique_ptr&lt;MCSubtargetInfo const&gt; &gt; anonymous{HexagonMCTargetDesc.cpp}::ArchSubtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a42d7fe1ef88cc2906006661704af630f">llvm::Hexagon_MC::getArchSubtarget</a>.</p>

</div>
</div>

### ArchSubtargetMutex {#a0772196a4e2b7dd77953b82267cb2cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex anonymous{HexagonMCTargetDesc.cpp}::ArchSubtargetMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a42d7fe1ef88cc2906006661704af630f">llvm::Hexagon_MC::getArchSubtarget</a>.</p>

</div>
</div>

### MV5 {#aea799c06a81ebc7804f0dfeb8c6abb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV5("mv5", cl::Hidden, cl::desc("Build for Hexagon V5"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV55 {#a4f8b07639f9e4ce4803ba229d3eb3092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV55("mv55", cl::Hidden, cl::desc("Build for Hexagon V55"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV60 {#ac9bbef802364faa2709eec2f557cb1af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV60("mv60", cl::Hidden, cl::desc("Build for Hexagon V60"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV62 {#a8bd7ac7fc67ff2e7071bea916c53166f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV62("mv62", cl::Hidden, cl::desc("Build for Hexagon V62"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV65 {#a59f962fd218d26a3e04afb9952ee42a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV65("mv65", cl::Hidden, cl::desc("Build for Hexagon V65"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV66 {#a405a78336379f05386ce4535451c9260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV66("mv66", cl::Hidden, cl::desc("Build for Hexagon V66"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV67 {#a946ef57fa8c3ddca341ec225dbfc9d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV67("mv67", cl::Hidden, cl::desc("Build for Hexagon V67"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV67T {#a4a352710d4ab7db74a7d33d71b585c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV67T("mv67t", cl::Hidden, cl::desc("Build for Hexagon V67T"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV68 {#af27b02a1ff6a77cde66910e6dae637d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV68("mv68", cl::Hidden, cl::desc("Build for Hexagon V68"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV69 {#ad19a56208855f807f2e8548d4e9f64f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV69("mv69", cl::Hidden, cl::desc("Build for Hexagon V69"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV71 {#a347bd13f61f1456fb3c8163449b460e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV71("mv71", cl::Hidden, cl::desc("Build for Hexagon V71"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV71T {#a69bf7aeb68398ee9123906db93ec61f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV71T("mv71t", cl::Hidden, cl::desc("Build for Hexagon V71T"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV73 {#ad58075072154993da11a73925cd864c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV73("mv73", cl::Hidden, cl::desc("Build for Hexagon V73"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV75 {#ab2b028f39911c18eaebbecd94de63eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV75("mv75", cl::Hidden, cl::desc("Build for Hexagon V75"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

### MV79 {#a5c8c1bc56cedd07c2a0a7433be767c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{HexagonMCTargetDesc.cpp}::MV79("mv79", cl::Hidden, cl::desc("Build for Hexagon V79"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
