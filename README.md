# Ghi chú TypeScript

Ghi lại các phần TypeScript mình đã học. Mỗi file có vài ví dụ nhỏ, đọc lại phần nào thì mở file đó.

## Cách chạy

Cần cài Node.js và npm trước.

```bash
npm install
npm run check
npm run build
node dist/05-enum-literal.js
```

Muốn chạy bài khác thì đổi tên file ở lệnh cuối. Sau khi sửa code cần build lại.

## Các phần đã học

- [01 - Kiểu dữ liệu, khai báo kiểu và suy luận kiểu](src/01-types.ts)
- [02 - Array và tuple](src/02-array-tuple.ts)
- [03 - Object và interface](src/03-object-interface.ts)
- [04 - Type alias, union và intersection](src/04-alias-union-intersection.ts)
- [05 - Enum và literal type](src/05-enum-literal.ts)
- [06 - Function, optional và rest parameter](src/06-functions.ts)
- [07 - Casting, unknown, type guard và assertion](src/07-casting-narrowing.ts)
- [08 - Class và kế thừa](src/08-class.ts)
- [09 - Generics](src/09-generics.ts)
- [10 - Utility types](src/10-utility-types.ts)
- [11 - Mapped types](src/11-mapped-types.ts)
- [12 - Template literal types](src/12-template-literal.ts)
- [13 - Symbol](src/13-symbol.ts)
- [14 - Promise, async/await, async iterator và generator](src/14-async.ts)

## Mấy chỗ dễ nhầm

- TypeScript kiểm tra kiểu lúc biên dịch. Dữ liệu từ API vẫn cần kiểm tra khi chạy.
- `as` không đổi giá trị thật. Muốn đổi chuỗi sang số thì dùng `Number()`.
- `unknown` cần kiểm tra trước khi dùng; `any` thì bỏ qua kiểm tra kiểu.
- `type` đặt tên được cho union, primitive, object... `interface` thường dùng cho object và có thể khai báo gộp.
- Template literal ghép hai union sẽ tạo mọi tổ hợp, không tự ghép đúng từng cặp.

Repo tham khảo khi học: [NodeJS-Course](https://github.com/itsdoanguen/NodeJS-Course/tree/main/Typescript).
