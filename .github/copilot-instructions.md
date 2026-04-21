---
description: Workspace instructions for the SocOps Blazor bingo game application. Always follow these guidelines when working with this codebase.
---

# SocOps Bingo Game - Agent Instructions

## Mandatory Development Checklist
- [ ] Lint code for style and errors
- [ ] Build project successfully
- [ ] Run tests and verify functionality

## Project Overview
SocOps is a Blazor WebAssembly bingo game for DevDays events, featuring interactive questions on social operations, DevOps, and software culture.

## Architecture
- **Framework**: Blazor WebAssembly (.NET 10)
- **Key Folders**: Pages, Components (BingoBoard, BingoSquare, etc.), Services (BingoGameService, BingoLogicService), Models, Data (Questions.cs)
- **Styling**: Custom CSS utilities in `wwwroot/css/app.css`

## Development Guidelines
1. **Blazor**: Use `@inject` for services, proper lifecycle and event handling.
2. **CSS**: Leverage utility classes; avoid inline styles.
3. **State**: Manage via services; use EventCallback for communication.
4. **UI Design**: Follow frontend-design instructions for creative, distinctive aesthetics.
5. **Build**: `dotnet build` and `dotnet run --project SocOps/SocOps.csproj` (runs on localhost:5166).

## Common Tasks
- Add questions to `Data/Questions.cs`
- Modify logic in Services
- Style components using CSS utilities
- Test builds and responsive design

Maintain the game's fun, interactive nature with Blazor best practices.
