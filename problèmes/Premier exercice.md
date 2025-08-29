---
jupyter:
  jupytext:
    main_language: python
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.16.0
---

<!-- #region tags=["problem-title"] -->
# Titre du problème
<!-- #endregion -->

<!-- #region tags=["problem-statement"] -->
Énoncé du problème
<!-- #endregion -->

## Contexte du problème

```python tags=["problem-context", "autoexec"]

```

## Entrez votre solution dans la cellule ci-dessous
Notez bien que **seul** le contenu de cette cellule sera **évalué** par le correcteur automatique.

```python tags=["user-answer", "editable", "autoexec"]

```

## Utilisez la cellule ci-dessous afin de faire vos tests. 
Notez qu'il est **inutile** de copier votre solution dans cette cellule, puisqu'elle partage le même interpréteur que la cellule de solution. À partir de cette cellule, faites **directement** appel aux éléments de votre solution afin de **bien** la tester.

```python tags=["user-tests", "editable", "autoexec"]

```

```python deletable=false tags=["reference-solution"]

```

```python deletable=false tags=["autograder-script"] id="autograder"

from hypothesis import given, assume, strategies as st


# main test procedure
def main(weight=90):
    pass


# make sure that solutions don't raise any exceptions
log = grader.check_exceptions()

if not log:
    # run main test procedure
    log = main()

# assign result logs
grader.log = log

```
