# Learn Enzyme

## References

[Code link](https://github.com/enzymejs/enzyme/tree/master/packages/enzyme/src)

## Code

mount(node, options)
  return new ReactWrapper(node, null, options);

shallow(node, options)
  return new ShallowWrapper(node, null, options);

ReactWrapper
  constructor(nodes, root, passedOptions = {})
    options = makeOptions(passedOptions)
