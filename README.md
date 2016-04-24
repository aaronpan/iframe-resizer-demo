## iframe-resizer-demo
Resize an iframe from another domain in multiple ways

## How to use

Copy the repo into your disk.

```bash
$ git clone https://github.com/aaronpan/iframe-resizer-demo.git
```

Then play with the source files under the repo's demo* directories.

## Index

1. [Subdomain iframe resize](#demo01)
1. [Use postMessage](#demo02)
1. [Web proxy for cross-domain iframe resize](#demo03)
1. [Use iframe-resizer library](#demo04)

---

## Demo01: Subdomain iframe resize

a.html in domain sub1.aaron.com
b.html in domain sub2.aaron.com

a embed b

This demo only works for subdomain cross-iframe.

## Demo02: Use postMessage

a.html in domain domain1.com
b.html in domain domain2.com

a embed b

Use HTML5 postMessage.

Support: Internet Explorer 8, Firefox 3, Opera 9, Chrome 3和 Safari 4。

## Demo03: Web proxy for cross-domain iframe resize

a.html and c.html in domain domain1.com
b.html in domain domain2.com

a embed b
b embed c

## Demo04: Use iframe-resizer library

a.html in domain domain1.com
b.html in domain domain2.com

a embed b

Dependency free, IE8+


## Related Projects

- [jquery](https://github.com/jquery/jquery/tree/1.12-stable)

- [iframe-resizer](https://github.com/davidjbradshaw/iframe-resizer)

## License

MIT