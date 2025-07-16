---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/passsupport-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PassSupport.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passinfo-h">llvm/PassInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include &lt;functional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass&lt;passName&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterPass&lt;t&gt; template - This template class is used to notify the system that a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> is available for use, and registers it into the internal database maintained by the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>. <a href="/web-llvm/docs/api/structs/llvm/registerpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> class - This class is meant to be derived from by clients that are interested in which passes get registered and unregistered at runtime (which can be because of the <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a> constructors being run as the program starts up, or may be because a shared object just got loaded). <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af807c9595d50b45c0008924c4679c85c">INITIALIZE_PASS</a>(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa970fc931c1c63037a8182e028d04b1">INITIALIZE_PASS_BEGIN</a>(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;  static void *<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##passName##PassOnce(PassRegistry &amp;Registry) {</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>(depName)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##depName##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#ab15af716dfa3d6f1fa7978be4639bd8e">Pass</a>(Registry);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ce8276b89067e806f67c45a6d92575">INITIALIZE_PASS_END</a>(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7fef7e9f9117f875aad5d6abaf99ce">INITIALIZE_PASS_WITH_OPTIONS</a>(PassName, Arg, Name, Cfg, Analysis)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace59d3535b2757db29feea7bcb1654cb">INITIALIZE_PASS_WITH_OPTIONS_BEGIN</a>(PassName, Arg, Name, Cfg, Analysis)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### INITIALIZE\_PASS {#af807c9595d50b45c0008924c4679c85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  static void *<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##passName##PassOnce(PassRegistry &amp;Registry) {        \
    PassInfo *PI = new PassInfo(                                               \
        <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, arg, &amp;passName::ID,                                              \
        PassInfo::NormalCtor_t(callDefaultCtor&lt;passName&gt;), cfg, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#abfa9bcfe6f0180f576c1a8c503ba2a03">analysis</a>);     \
    Registry.registerPass(*PI, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                                          \
    return PI;                                                                 \
  }                                                                            \
  static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a> Initialize##passName##PassFlag;                       \
  void <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">llvm::initialize</a>##passName##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#ab15af716dfa3d6f1fa7978be4639bd8e">Pass</a>(PassRegistry &amp;Registry) {              \
    <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>(Initialize##passName##PassFlag,                            \
                    <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##passName##PassOnce, std::ref(Registry));       \
  }
</div>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN {#aaa970fc931c1c63037a8182e028d04b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS_BEGIN(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;  static void *<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##passName##PassOnce(PassRegistry &amp;Registry) {</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a2629010d4dd1192ddb70b0f785a00cdd">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a2338bae954f68157db5b0f0e01f5be14">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a59de456979d573be6599fcd0448f2ae4">INITIALIZE_PASS_BEGIN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp/#ae03f82d6e49a61523c78050b29420f68">INITIALIZE_PASS_BEGIN</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_DEPENDENCY {#a14724f1ccf528e73bb29bc9230737967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS_DEPENDENCY(depName)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##depName##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#ab15af716dfa3d6f1fa7978be4639bd8e">Pass</a>(Registry);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#a348b753888c4978293fa70574c9682f1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionoptimizer-cpp/#ac818f8162115c72d768624629ff70116">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp/#a5d90ef434c159196dae67c190f33bf6b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64postcoalescerpass-cpp/#aec06d04ac99d006657516b67e6a8452c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizercombiner-cpp/#a11bfb0068d20bffc5709fe773ae2c3de">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp/#add6a10c10fdbc00ddb2ae110effc4184">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64prelegalizercombiner-cpp/#a1fda6d089b2a76e503b07240b097d9e6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#acddbaf5fc5a8735431a050af39909d9f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a2d690ea61c793e992109e982ebd96677">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a387f65094ae15ae3b17f54f9fec20492">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a4422f5c583f55c63cb0af582c285c04a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuannotateuniformvalues-cpp/#a984b1ee112fb0b50753d84ea6a31d643">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#aed004afef48c2e344a88ab6cac2cd819">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp/#ad0cb484e775797726c8319d9193cc4a2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a976c834604c38d6c619811a1f2602c5a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a90c2bc4d644df490415b889da2edab6a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliseldivergencelowering-cpp/#a8cca4cfc58ac92b065504bb967429439">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp/#a96849361d3aa08283065a702583a7e0a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a4e69754951eb68f49044becfc751eab6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#aa0e85c2b5ba873a205f7fab46756e5a2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a50e8288d4307b3bbb5cb7663c25773ff">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupostlegalizercombiner-cpp/#a7b34ddf92eb380e8081e6ddd566c9298">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuprelegalizercombiner-cpp/#ad0c3a7f193f5cac9c0537f4ce4b6d387">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuprintfruntimebinding-cpp/#a8cde8a72c5e4333107eedc64cf8f9f14">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ad2e5833b86d7317e2d42fa86cee07635">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a2629010d4dd1192ddb70b0f785a00cdd">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotekernelarguments-cpp/#a750138d044f791efcacb32e6b757fd74">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankcombiner-cpp/#ac535dbd1d443cceb202ec360af8d503f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#ac55b04d6f62a8faacd9fab2f2c4072ad">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a2b0ff7672275b7b589f6fe1c43569a1b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteoutarguments-cpp/#ad7a3fe52c4f607f41ff8c31a8bb71dd1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#aca7cdd32c08e551ff6c01a4a54ae03b1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp/#a2dfc3765b1a54067eaf6df1e9a7c4c09">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#a0d32894325cbeced352d98bbd0465a8d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp/#a1e336498b652193459f31ade7e688900">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a84c0cf3f354dd3f62de4caae31e719d5">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a4f604a8df9eb00990e08e7a415da25e6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armfixcortexa57aes1742098pass-cpp/#a46d73a38481744df43ff65a3b35bcd6a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ae90fd60a479cc1f31ac8ed3c13db154c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a2b5dd836d681863bc1cf1ab9fdcd3a90">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8f78a461faf84de1eca1d5333177ff96">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblockpathcloning-cpp/#aac2ca1b86d9a2310861abcc71ebfab06">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ae6a302780ed34373cb384b67a94940f5">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a016177254de2446a59c8933b3ce3a085">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a2c0db623aadd71d3caf0937e7c830691">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a1b7e9de6c7bb0d3e1f040c3eabaee26c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp/#a482c643aa917a4852d96dcea88cf7a88">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#a36042f95d95c690cd9e423f61d7a3c0c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#aaca449a7620b1306ed7586ba6bdc4faa">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a93f57b76764f70277aa130c9b4604eac">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a151582df001d28a64091860aed399832">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dominancefrontier-cpp/#acd2bd1fe4668f13c491f65a4229d9187">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dwarfehprepare-cpp/#ad5bb192956735b7d0764ee17afa89c00">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a68619ff4a2bbf3f93a52743885e179ad">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a71acd06925b6ca5abcd7f9c49690f722">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprepare-cpp/#a89520979dacc516772b21ee40afed920">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7d6328e1cd0513593c138d4b79e2bf4e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a6832a78dbbad6c47769e155eed09a550">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a90d937bdea112bd5a0265434e6385967">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#a3503a7cbe1d709c109b2c4e25e790f7e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#a0b4246eb7f405a8ddcd7dab6f2d7ee86">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a84e077ca7a4823dbc58f9d89f325c01d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a5d947747198750258589494add351c1b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a2338bae954f68157db5b0f0e01f5be14">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandmemcmp-cpp/#a4aa08769fc67ad00c1c9c1db060fc086">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandreductions-cpp/#a3649810f5e74e169545039f65070785b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#ad7b9232649998355c29c264a961048c6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a2584dedbce90b923d352bca064ed2416">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a67e827d2427f074f00ef13822890ca20">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/flattencfgpass-cpp/#a8b74d0aeb08b45b80f2d4e598bc0fc92">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#a5bfe00926b7e887b5837592ace8c6d93">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnnsareassign-cpp/#ac5fd3b2663d31468f5c04953a1480495">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnpreraoptimizations-cpp/#a232a335d4de61c05edb518bda8b84f6a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp/#a783b0b0afa351778fad65fb812b63b40">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#ad1b90f235bd43ec479634ac89c9bb85a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ab57fa9ac6cd9430d8538c67be931255d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstextenders-cpp/#a048e8eae1ec9d41fc4f3b57a6e511997">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonexpandcondsets-cpp/#a44f9975d1bf1b334597df7a76e396b40">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenextract-cpp/#a80c190d9a275cfd300ac9d8243b00f2f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp/#a3b758f533a8fb5d47f21a5669055f16e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a7be652ace3a2029317c80d7439b89f9c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#a006bdae8132fee09f0c1630f24e42dc2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a59de456979d573be6599fcd0448f2ae4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-cpp/#a9f9c08c80df6200ae732d38e35f50cfe">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a603ae8c2df43d9a8ac70780216b1e63b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#a33487f01432b5dd545d85ef0e03c62a6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#ae224b6ca05cea968d2c7a22b6888a2d2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp/#ad944d59f070d5ce085cd157007f31689">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#ac792f731c979b10ac2997a28886fbaca">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp/#a72f37dd21acba427b40ff02b2cccaaf7">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp/#ab035865c5f72d933157bf6cf72b187c7">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a8ff15fa8059975382b437c6198645ce6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a3212c2593aa48f6720eb08140b8f7823">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#ad7579e1a53b2bc762bcce3918a7d8533">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a8a787de77e16e56d936abb2ad6ee4c8c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp/#aba183f31c50f2198381047dcbc71b78b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#ad9cd2449bd89ad2d38e5717ff6c0f7b9">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#a0e9e632235937440bcbf94b6751161d3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp/#a95181f7ffbdc116d7e78eeb2d5501374">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#a064a4e1a89aeabcb889d67250ca4f2c7">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a7a1fcb74d592fe46a83968418fe162e9">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyblockfrequencyinfo-cpp/#a5abe31c97e96a1137c330560c16941c1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazybranchprobabilityinfo-cpp/#a8f6939e1a8bf2941411cbcffc6079485">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lazymachineblockfrequencyinfo-cpp/#a5e1302d885ccb9d2ccc5f42e3bf82a2d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac62283130ff1d80a036fae76f36ed1f4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a98a801b39a5e46df56fa71e79bef80e6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aea8a4c201b5630473d49bddbb5f5c221">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#af3a321241cc2af15a42a976d4050fbf4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a968d037e7d8a094b89bd06e59567b21f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#af96d5ead32e826426be894bdb930ca72">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#ae25c51998eaa90d23fa08def51f03096">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livestacks-cpp/#a7528c61ecf11c987d79b33469735efbe">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp/#ab03e43a0d8aa902145be6d17a1e8aac8">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#acedacdca2ca031ad47baf9b94d303196">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#ab2039397dd7d5dee3656f5100ff69262">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp/#a4aa37a07ffe2b7fb67aef09027c7c59e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a3e75b43fc855af806f16b3faff0930f7">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a4c965a1b6ebfc575d31753d55973b102">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a557c0d5181dc3dadb614f9fd12a9c18f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a0cf26a507ec1ff72dd6624ac9b69d05c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a7bc54216250fbed39fc7a20c8947d90c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#af6a8fc5324b2cf8a0a85f04893fada09">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerswitch-cpp/#acaba83c5d6bd77aec805628d1a1e2e9a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp/#a55ef98beab270065d5306abae2018a20">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#aa4d0eea634133a91f99ee833a4d073ef">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#ace73c7d6fee046409626ebb1799d0454">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a784c65381eb8b622eecb204b03ea6143">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecse-cpp/#a2b482340f6d5559b1505ae2eaa3a9c1d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecycleanalysis-cpp/#a6d03c71c069635597085addf14df21ee">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedominancefrontier-cpp/#a6579ad0678b2fc7eab055f5828115184">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a6151e46d654441cc8d36881a0c2effc2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp/#aba49c2047fb02b8ddb70f699b9070908">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp/#aad092d1a418629cb8fbdbd309b7f5e0b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#adc6a728bf35f2a3eb9aae797607ad621">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregioninfo-cpp/#a0870ae045a051348f4e337d40bae7a33">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a43709087555742d45e0c99ab89ac1df3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a8ecbf0fad9948bab3c145b46cbf244f4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6e5eb2a62e2a3166442dc41707855ee9">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp/#ac84cf7a8a6d35ca67221808bbe77e30e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp/#a64125f99a2aa1a1f82e3a21f7191554d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a865dea47ca1862c87d7bed49760b9133">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a72507946850fcd3cdea22735440c5a83">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp/#a8a8f56f7116a05670b7fb305df41ccd1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipspostlegalizercombiner-cpp/#aeb0415f75644c7551012ce7308f6ab6d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsprelegalizercombiner-cpp/#ac7e32dd29e19def582a680da392f1f08">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a29679164c681da5fc6cdcaa0b39538a3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#af072630d86644c22c7d47b0008668581">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#ae1ec89e71fd305c8a25e468cf1ab2392">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#ad716436318a37e9b4fdf6a2e1ae89213">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/naryreassociate-cpp/#a7d4c2930b86591ba670b7b467611b54e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a0370c56be3c5d1e1fd720eff6878a0d2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp/#a3668c5d4dc4e9f49a6b19b98a234e950">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp/#ad1653a0117b4de119ad96161d659e25c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3015df5e1d804164183ed31f7f6c7917">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#adf5adc995d8418fe6f69a4613b0541fa">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a40ebb63853243050bfbf89f7d9c690fb">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a354b6898ee4370a234f0d91a2c47e399">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#ad1700270c8c097e34addb88dc823bf77">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a27a533bd7164c44dcf8b7ecaf3002893">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a219604df9ff809f1af95c0ead787c789">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp/#a6578139db9d0dfc0f21a1ee2cfbaa5da">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloops-cpp/#a864f15eedf26c81729e18a20adee7306">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#ae138719f744d370b3dabf2d8588ae069">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmipeephole-cpp/#a739097ef1a5210b8b513203591090691">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a16ce2a7c2ae9d297060b3a893cba0fa6">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#ae005d66f0db86d0d82cfce05120c6563">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a3b0be7020c195aa7d0eeb789b6374395">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#ae273d5c59199105d9ef76fea7930c491">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a0c73d2613729ae023beb9bb5f0813430">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudoprobeinserter-cpp/#ada78c80aa2afebcfc578e8ec3c64e1ff">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a67805c1890335f2d3e28410af2931232">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#a37d002c2a57c5f40bc24a769615f7319">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a3432e3b6c401a63f0a4669eea84041cb">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a29216cc159b4d414b01b0cd232c381cf">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#af060f5a17701ea45bc64cd57b59799e4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfocollector-cpp/#a0bccbe5951e764fbc019385ef3f6b3e0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfopropagate-cpp/#a13b21d85f6835bee9409725c1b41196b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/renameindependentsubregs-cpp/#a96d411dcb6e6f9fbb712d2d5b6fe3c33">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a85427e4c08946a31d58c98744d23417d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvo0prelegalizercombiner-cpp/#a8199749e1eb2d3a631418184fc3da4cf">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvpostlegalizercombiner-cpp/#a8b989ede23ebcc6699eef46066320429">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp/#a0fc716846aed6abede1e500fb725de37">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#af3163a4fcb7dbce7f61ad71c82d7dbbd">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp/#a673fb998c8c39b9cdeb67a6625195369">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a3e24c91db8604ae3ee873162c89749d3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#ad71bcc32aba45ffc41c59fe45487943b">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp/#aff0fc8e4abb69494974e0d5baa2e6d4a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionaliasanalysis-cpp/#ac924eaf0d4e6e89c849f9319d66f1a28">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#aab588fc778ee5107e3aafae0f569143a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#abf52a2545b4ce2ba2c0835ffaafc5f07">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-cpp/#a8a615e42c51081c909b8818b6a532aec">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shadowstackgclowering-cpp/#a42f0de9c853c595cc4fbb96b658fdc44">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siannotatecontrolflow-cpp/#a424f7d910dc544025f7a2ef089f55dd4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a585b8597ec23b3b73e8dcd60a8ed7fa0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#a2a7e30fea033fbd7e0107dc00b4fc2f4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a87d0ba229f3fffeaafd9aba7162ba52e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a8cc43543321447af9ffa3b2695bfb278">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp/#af5379899a691419f602668b08ac5d730">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a00cc59e0f9e6e504dde71ffe07ffd073">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a66ecd9fb24df9739558533d8a35d68db">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowerwwmcopies-cpp/#a6267a058b60c3343a25164ee058dedf1">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#ac293a877ec698f80a304fe926f0704f2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3adf5343de747616c8d71ea58ec06f25">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp/#ad745a4d895a366bdfc3486d667aaa3b2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipreallocatewwmregs-cpp/#acf6b41676b4936673c00606c6298bd49">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siwholequadmode-cpp/#a320bfee867eaf92bf11ea43d449609e5">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#a88c259b2d1614b950ce01eb81b5b47b5">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp/#a546ba6a1a0e4442c6868173de57ca4ed">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp/#acfb44fedf6cd2a76472b12870227374d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvmergeregionexittargets-cpp/#a868ca3fe0fd08206fc3aff44a1353baa">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizercombiner-cpp/#aa60f51552735338b1fbd8e0fa7c04d1e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvstructurizer-cpp/#a02660c07fa72a3715784a054d81905dc">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a786d5a99befacdb30b3d3b5c3b07bd30">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#a4cb1c1ecb52c8f4f676c55e1868ecf99">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a4a14dc9854abe8f3e2bda2e4b62b5a99">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp/#ae03f82d6e49a61523c78050b29420f68">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp/#a829968fc829797e399d7bd2bc94226e2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackslotcoloring-cpp/#a6c402a7f8723dce66b65f5db8ea5d294">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#a8929a6375e9d84ce1c667aa9e961de44">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/straightlinestrengthreduce-cpp/#adccbe65e000351716a1012a5f315786a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp/#aec6c42f972ff6a31d7483b408a246b3f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#a90ebd8ea349f793ffbebee0995e151ec">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a7cd1da73ec22771e086d129cd2af39a3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp/#a91234e20d6189c6bcb7698b9f4ba10c9">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#af789701014d452a6764baa46d6afa7e0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#aa1345d5c2e7fc345dbafc2528778efb4">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexceptioninfo-cpp/#a2c727f88e453cb5a87d1cd6810639d8f">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriterpass-cpp/#a24c8a27ae2b9fa83a83d5b89c3003b34">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilwriterpass-cpp/#ae58769477f4580031f125e25adfeac42">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a2e24170138c75869c19d0785e9b7ed99">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86cmovconversion-cpp/#a862457c987dbf7432ed0610ab137992c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#ae18ac924a0d56c77a8e0a323f797fa39">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp/#a415cc17a725369e07f7faa8e9b4ee998">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#ae652287d9b56224da1497ec0c3fe455a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a2137b1559a07e8633b8c8ee6dcec8fc0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86pretileconfig-cpp/#a77b632b1fb91ac1e4e292aa337706af0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#af94ae919f186a9c0e5fc5bbf470c196d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/xrayinstrumentation-cpp/#a680b0479c3d05078d5b490037f0686e3">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#a2bb87eb1bcbc74783a83ae945eb8fa36">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a965e91729ab517bcb1f93f10f100f95c">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a237a31a1c24891f4ea0bf3b9910de839">llvm::initializeLazyBFIPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21acd6e20755cf5614f8c014742c5896">llvm::initializeLazyBPIPassPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa73880de517c04ff09f5bc0f48b3ba">llvm::initializeLoopPassPass</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_END {#a74ce8276b89067e806f67c45a6d92575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS_END(passName, arg, name, cfg, analysis)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  PassInfo *PI = new PassInfo(                                                 \
      <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, arg, &amp;passName::ID,                                                \
      PassInfo::NormalCtor_t(callDefaultCtor&lt;passName&gt;), cfg, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#abfa9bcfe6f0180f576c1a8c503ba2a03">analysis</a>);       \
  Registry.registerPass(*PI, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                                            \
  return PI;                                                                   \
  }                                                                            \
  static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a> Initialize##passName##PassFlag;                       \
  void <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">llvm::initialize</a>##passName##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#ab15af716dfa3d6f1fa7978be4639bd8e">Pass</a>(PassRegistry &amp;Registry) {              \
    <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>(Initialize##passName##PassFlag,                            \
                    <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>##passName##PassOnce, std::ref(Registry));       \
  }
</div>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp/#ad0cb484e775797726c8319d9193cc4a2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblockpathcloning-cpp/#aac2ca1b86d9a2310861abcc71ebfab06">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#a3503a7cbe1d709c109b2c4e25e790f7e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp/#a95181f7ffbdc116d7e78eeb2d5501374">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#af6a8fc5324b2cf8a0a85f04893fada09">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp/#a68842bc3b5fabe1380dbe92570b2959c">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecycleanalysis-cpp/#a6d03c71c069635597085addf14df21ee">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp/#a64125f99a2aa1a1f82e3a21f7191554d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3015df5e1d804164183ed31f7f6c7917">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#ad1700270c8c097e34addb88dc823bf77">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a27a533bd7164c44dcf8b7ecaf3002893">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#ae273d5c59199105d9ef76fea7930c491">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#abf52a2545b4ce2ba2c0835ffaafc5f07">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp/#acfb44fedf6cd2a76472b12870227374d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp/#a829968fc829797e399d7bd2bc94226e2">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#a2bb87eb1bcbc74783a83ae945eb8fa36">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a965e91729ab517bcb1f93f10f100f95c">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armfixcortexa57aes1742098pass-cpp/#aad909330eea5e4799c44e96cc8dba2bd">INITIALIZE_PASS_END</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#a45a3f96bc41116cda91360fda4b2e42a">INITIALIZE_PASS_END</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp/#a0eee13989797c0d4612066f84ff7a7b8">INITIALIZE_PASS_END</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_WITH\_OPTIONS {#aaa7fef7e9f9117f875aad5d6abaf99ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS_WITH_OPTIONS(PassName, Arg, Name, Cfg, Analysis)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#aaa970fc931c1c63037a8182e028d04b1">INITIALIZE_PASS_BEGIN</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, Arg, Name, Cfg, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>)                    \
  PassName::registerOptions();                                                 \
  <a href="#a74ce8276b89067e806f67c45a6d92575">INITIALIZE_PASS_END</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, Arg, Name, Cfg, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>)
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_WITH\_OPTIONS\_BEGIN {#ace59d3535b2757db29feea7bcb1654cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INITIALIZE_PASS_WITH_OPTIONS_BEGIN(PassName, Arg, Name, Cfg, Analysis)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#aaa970fc931c1c63037a8182e028d04b1">INITIALIZE_PASS_BEGIN</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, Arg, Name, Cfg, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>)                    \
  PassName::registerOptions();
</div>
</dd>
</dl>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
