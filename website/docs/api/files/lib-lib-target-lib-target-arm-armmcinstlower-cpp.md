---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armmcinstlower-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMMCInstLower.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arm-h">ARM.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-h">ARMAsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">MCTargetDesc/ARMAddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">MCTargetDesc/ARMBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcexpr-h">MCTargetDesc/ARMMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
