# Active context — поточний фокус

> Оновлюй цей файл, коли змінюється **що саме** робите в найближчі дні / сесію. Так агенти одразу бачать актуальне, а не лише статичний brief.

## Поточна гілка / етап

- Репозиторій: форк Excalidraw, воркшоп (Memory Bank + документація + Cursor).
- За потреби вкажи гілку git тут: _(доповни при роботі над фічею)_

## Зараз у пріоритеті

- Підготовка PR Day 2 (чеклист у `.github/PULL_REQUEST_TEMPLATE.md`): переконатися, що `yarn build` пройшов перед здачею.
- Бонус Repomix: reference skill у `.cursor/skills/repomix-generated-docs/` — готово; за потреби оновлювати повторним `npx repomix --skill-generate`.
- Уніфікація комунікації: українська за замовчуванням (`.cursor/rules/project-communication-language.mdc`).

## Відкриті питання

- За потреби додати ще 1-2 domain-specific rules після фідбеку рев'ю (не обов'язково для мінімального проходження N2).

## Що не чіпати без потреби

- Великий рефактор `packages/excalidraw/components/App.tsx` без тестів і чіткого плану.
- Публічні `exports` у `packages/excalidraw/package.json` без оновлення прикладів.

## Корисні посилання на код

- Стан редактора: `packages/excalidraw/types.ts` (`AppState`)
- Дії: `packages/excalidraw/actions/`
- Модель елементів: `packages/element/src/types.ts`
