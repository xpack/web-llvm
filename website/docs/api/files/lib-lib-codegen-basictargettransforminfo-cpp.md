---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/basictargettransforminfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BasicTargetTransformInfo.cpp` File Reference

<p>This file provides the implementation of a basic <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> pass predicated on the target abstractions present in the target independent code generator. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">llvm/CodeGen/BasicTTIImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Description {#details}

<p>This file provides the implementation of a basic <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> pass predicated on the target abstractions present in the target independent code generator.</p>


<p>It uses these (primarily <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a>) to model as much of the <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> query interface as possible. It is included by most targets so that they can specialize only a small subset of the query space.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
