# CSS Specificity Bug

This repository demonstrates a common issue encountered when working with CSS: unexpected style overrides due to specificity conflicts.  Inline styles, having the highest specificity, can unintentionally override styles declared in external stylesheets or `<style>` tags, leading to unexpected layout changes.

The `bug.css` file contains the problematic CSS. `bugSolution.css` shows how to address the issue.