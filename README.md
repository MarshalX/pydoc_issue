```bash
pip install pdoc3
pdoc test --html -c show_inherited_members=True --force    
```

# Ref

**https://marshalx.github.io/pydoc_issue/html/test/test2.html**

## Actual behavior

method1 of class test2 is not displayed.

## Excepted behavior

method1 should display as method2 but with mark "Inherited from".

## Additional info

If I add a docstring to method1, it will appear (method0 as an example).
I would like to appear this method with an empty docstring.
