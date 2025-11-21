# Strategic Glycan Engineering Scanner

**Proof-of-Concept Tool for Identifying PTM Engineering Sites in ML-Designed Antibodies**

⚠️ **Status: Preliminary - Requires Experimental Validation**

This scanner identifies positions in antibody sequences where single mutations 
can create N-glycosylation sites, prioritized by somatic hypermutation probability.

**Intended Use:** Screening RFdiffusion-designed antibodies for strategic 
glycan engineering opportunities before MD validation.

**Limitations:** 
- Thresholds not experimentally validated
- Requires MD simulation follow-up
- Sequence-only analysis (structure integration in progress)

**Citation:** If you use this tool, please cite: [paper/preprint when available]

---

## The Real Workflow

This scanner is **Step 2** in a larger pipeline:

1. RFdiffusion generates antibody
2. **This scanner identifies engineering sites** ← You are here
3. MD simulations validate glycan additions (proprietary)
4. MMPBSA ranks candidates (proprietary)
5. Expression testing (experimental)

For consulting inquiries about the complete workflow: clgaughan@proton.me.com
