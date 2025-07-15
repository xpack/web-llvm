---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoongArchMCInstLower.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarch-h">LoongArch.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">MCTargetDesc/LoongArchBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">MCTargetDesc/LoongArchMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a> (const MachineOperand &amp;MO, MCSymbol *Sym, const AsmPrinter &amp;AP)</td>
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

### lowerSymbolOperand() {#a931cec5e0b9faa60b9b6943de522e49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand lowerSymbolOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp">LoongArchMCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#aa9ef99fc9b815bad6647b7ee1c5b4161">llvm::LoongArchMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#ab4d10aeb6baa9b7d22a3e7a108243e7a">llvm::LoongArchII::getDirectFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a2f9fa0e4abfc14d359493021fdef57ca">llvm::LoongArchII::hasRelaxFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a47cd4b1e13d896a3c839c26ce7c9bace">llvm::LoongArchII::MO_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a25d2eba87ca5c835c21760f9720504d9">llvm::LoongArchII::MO_CALL36</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078adc1fe3e72c9d5fd9003f77dfbf61505a">llvm::LoongArchII::MO_CALL_PLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a77a0574b3dc8b83f538804f8e3df84d7">llvm::LoongArchII::MO_DESC64_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ab395ff3151115b55c5e9bdccdab63a79">llvm::LoongArchII::MO_DESC64_PC_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a2ed9da17c1681309f48f9bc32dbfa333">llvm::LoongArchII::MO_DESC_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078af6ed8cbbc6b55692f6bd04e284ac92a3">llvm::LoongArchII::MO_DESC_LD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a375020882b17576e0993863147dc34c7">llvm::LoongArchII::MO_DESC_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ad04fda120f5e018a803ae4369fe00043">llvm::LoongArchII::MO_DESC_PC_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a4c0eba82d8842c407247ba4c0345122d">llvm::LoongArchII::MO_GD_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ab02370623a4c55790186678faff4fffa">llvm::LoongArchII::MO_GOT_PC64_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a53c989ca902e693043ae60d02625c853">llvm::LoongArchII::MO_GOT_PC64_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a4cf49e1eebba4fe318b1e60b142e7a1d">llvm::LoongArchII::MO_GOT_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a14482ab8d5abc3ee10f93dd895bd65a5">llvm::LoongArchII::MO_GOT_PC_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a611c28719399932181f6d2f07b0e241b">llvm::LoongArchII::MO_IE_PC64_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ae31981e988e08f34a895090659048017">llvm::LoongArchII::MO_IE_PC64_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a6ef876630029cffa0fc2581b6f2a6cbd">llvm::LoongArchII::MO_IE_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a4cdf03d43999841e402cd1058c9ba6d8">llvm::LoongArchII::MO_IE_PC_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a1d89198c1efc61c0a7bf6e50c994425c">llvm::LoongArchII::MO_LD_PC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ad93e0f18f610cdb34229ab6ecca73ec7">llvm::LoongArchII::MO_LE64_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a31822c312e2327e2cf3d688abb94671d">llvm::LoongArchII::MO_LE64_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078aa5960be7a10593432cac2a48ba0130b6">llvm::LoongArchII::MO_LE_ADD_R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078abe9ec4f9a1d5546b5b27426640726240">llvm::LoongArchII::MO_LE_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078aa9b58d2f9b15720c61836b790e67df8a">llvm::LoongArchII::MO_LE_HI_R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a570b6df712e56db765351bc63a4774ec">llvm::LoongArchII::MO_LE_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078af7ae9605028f7b775ea830206d1fee8d">llvm::LoongArchII::MO_LE_LO_R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a7e0b3356a9a3617e6341ea02d6275cb3">llvm::LoongArchII::MO_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ac204c91c6c9f520505f55f5ccf012136">llvm::LoongArchII::MO_PCREL64_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078ae1dcf847f8f53350ba32361bfda5bb5c">llvm::LoongArchII::MO_PCREL64_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a5e18166bf3ee69c16c30ada264da3067">llvm::LoongArchII::MO_PCREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a0048a64a7cbea49becaf00a3877006ed">llvm::LoongArchII::MO_PCREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa1966ed6149cfdacca4a00fe4c47c84b2">llvm::LoongArchMCExpr::VK_LoongArch_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab">llvm::LoongArchMCExpr::VK_LoongArch_CALL36</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5">llvm::LoongArchMCExpr::VK_LoongArch_CALL_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_LD</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_ADD_R</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20_R</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12_R</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
