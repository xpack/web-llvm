---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/aarch64ccmp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The CMP;CCMP matching Reference

<p>These functions deal with the formation of CMP;CCMP;... sequences.</p>

## Description {#details}


<p>The CCMP/CCMN/FCCMP/FCCMPE instructions allow the conditional execution of a comparison. They set the NZCV flags to a predefined value if their predicate is false. This allows to express arbitrary conjunctions, for example "cmp 0 (and (setCA (cmp A)) (setCB (cmp B)))" expressed as: cmp A ccmp B, inv(CB), CA check for CB flags</p>


<p>This naturally lets us implement chains of AND operations with SETCC operands. And we can even implement some other situations by transforming them:</p>


<ul class="doxyList ">
<li>We can implement (NEG SETCC) i.e. negating a single comparison by negating the flags used in a CCMP/FCCMP operations.</li>
<li>We can negate the result of a whole chain of CMP/CCMP/FCCMP operations by negating the flags we test for afterwards. i.e. NEG (CMP CCMP CCCMP ...) can be implemented.</li>
<li>Note that we can only ever negate all previously processed results. What we can not implement by flipping the flags to test is a negation of two sub-trees (because the negation affects all sub-trees emitted so far, so the 2nd sub-tree we emit would also affect the first). With those tools we can implement some OR operations:</li>
<li>(OR (SETCC A) (SETCC B)) can be implemented via: NEG (AND (NEG (SETCC A)) (NEG (SETCC B)))</li>
<li>After transforming OR to NEG/AND combinations we may be able to use NEG elimination rules from earlier to implement the whole thing as a CCMP/FCCMP chain.</li>
</ul>

<p>As complete example: or (or (setCA (cmp A)) (setCB (cmp B))) (and (setCC (cmp C)) (setCD (cmp D)))" can be reassociated to: or (and (setCC (cmp C)) setCD (cmp D))</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
