# TodoApi

.NET 8 Minimal API로 만든 Todo REST API 학습용 프로젝트입니다.

## Tech Stack

- .NET 8 (`Microsoft.NET.Sdk.Web`)
- ASP.NET Core Minimal API
- Entity Framework Core (`Microsoft.EntityFrameworkCore.InMemory`) — 인메모리 DB

## Endpoints

| Method | URL | 설명 |
|---|---|---|
| GET | `/todoitems` | Todo 전체 조회 |
| GET | `/todoitems/{id}` | Todo 단건 조회 |
| POST | `/todoitems` | Todo 생성 |
| PUT | `/todoitems/{id}` | Todo 수정 |
| DELETE | `/todoitems/{id}` | Todo 삭제 |

## 실행 방법

```bash
dotnet restore
dotnet run
```

## 학습 노트

과정을 정리한 노션 페이지: [TodoApi 실습](https://app.notion.com/p/TodoApi-3b94f47a5b3280d6b9c2fa04da25eadc?source=copy_link)
