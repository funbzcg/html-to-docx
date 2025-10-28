```bash
npm install @funbzcg/html-to-docx.
```

```js
import { useCreateDocx } from '@funbzcg/html-to-docx.';
/** html字符串，内联样式 */
const html = ''
let o = useCreateDocx(html);
// 导出 docx 的 blob
const blob = await o.docxAsBlob();
// 导出文件
saveAs(blob, `文件名.docx`);
```
