[![Published on webcomponents.org][webcomponents-image]][webcomponents-url]

# \<s-rating\>

Ultra fast Polymer elements for ratings.

Based on Reduce Cost performance pattern:

- reduce composition overuse
- reduce work in ready / attached
- use CSS for dynamism
- reduce use of default values
- defer work until after render

Check out the [demo and full documentation][webcomponents-url]

![s-rating Demo](https://cdn.rawgit.com/StartPolymer/media/master/s-rating/s-rating-demo.png)

![s-rating Performance](https://cdn.rawgit.com/StartPolymer/media/master/s-rating/s-rating-performance.png)

## Usage

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="s-rating.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<s-rating value="3"></s-rating>
```

## Installation

`bower i s-rating -S`

## Resources

- [Do Less & Be Lazy: Practical Performance Patterns for Polymer (Polymer Summit 2016)](https://youtu.be/hHC9EOJzrQk?t=16m10s)
- [polyperf](https://github.com/PolymerLabs/polyperf)
- [ratings-element](https://github.com/PolymerLabs/polyperf/tree/ratings-element/elements/ratings-element)

## License

MIT: [StartPolymer/license](https://github.com/StartPolymer/license)


[webcomponents-image]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://beta.webcomponents.org/collection/StartPolymer/s-rating
