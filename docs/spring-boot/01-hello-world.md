# 01 - Hello World

## 本堂目標（30 分鐘）
- 建立 Spring Boot 專案（Java 17 + Maven + Spring Web）
- 寫出 `GET /hello` 回傳 JSON
- 會用 `curl` 測試

## 最關鍵 20%
- `@RestController`：把 request 對應到 method，回傳會自動轉 JSON（Jackson）
- `@GetMapping("/hello")`：最小路由

## 最小範例
```java
@RestController
public class HelloController {
  @GetMapping("/hello")
  public Map<String, Object> hello() {
    return Map.of("message", "hello spring boot", "ok", true);
  }
}
```

## 15 分鐘覆盤（照填）
- 我今天做了什麼：
- 3 個關鍵概念（用自己的話）：
- 我卡住/我學到的坑：
- 下一堂想弄懂的問題：
