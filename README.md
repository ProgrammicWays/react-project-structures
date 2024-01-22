# react-project-structures

## Flat Structure
        src/
        |--- components
        |--- styles
        |--- assets
        |--- utils
        |--- App.tsx
        |--- index.tsx
        
## Component Based Structure
        src/
        |---- components
        |-------- Header/
        |----------- Header.tsx
        |----------- Header.css
        |----------- Header.test.tsx
        |-------- Footer/
        |----------- Footer.tsx
        |----------- Footer.css
        |----------- Footer.test.tsx
        |---- App.tsx
        |---- Index.tsx

## Feature Based Structure
        src/
        |--- Features/
        |-------- Dashboard
        |----------- styles
        |----------- assets
        |----------- components
        |----------- types
        |----------- utils
        |----------- dashboard.tsx
        |----------- dashboard.test.tsx
        |-------- Profile
        |----------- styles
        |----------- assets
        |----------- components
        |----------- types
        |----------- utils
        |----------- profile.tsx
        |----------- profile.test.tsx

        |--- App.tsx
        |--- index.tsx

## Atomic Design Structure

        src/
        |---- atoms/
        |------- Button/
        |--------- Button.tsx
        |--------- Button.styles.ts
        |---- molecules/
        |------- Form/
        |--------- Form.tsx
        |--------- Form.styles.ts
        |---- organism/
        |------- Header/
        |--------- Header.tsx
        |--------- Header.styles.ts
        |---- templates/
        |------- thee-column-layout/
        |--------- thee-column-layout.tsx
        |--------- thee-column-layout.styles.ts
        |---- pages/
        |------- Home/
        |--------- home.tsx
        |--------- home.ts
        |---- App.tsx
        |---- index.tsx

## Hybrid Structure
        src/
        |---- components/
        |-------- common/
        |---------- Button/
        |---------- Input/
        |-------- feature1/
        |---------- components/
        |---------- container/
        |---------- assets/
        |---------- styles/
        |---------- utils/
        |-------- feature2/
        |---------- components/
        |---------- container/
        |---------- assets/
        |---------- styles/
        |---------- utils/
        |---- features/
        |-------- feature1/
        |---------- services/
        |---------- reducers/
        |---------- actions/
        |---------- slices/
|-------- feature2/
|---------- services/
|---------- reducers/
|---------- actions/
|---------- reducers/
|---------- slices/
|---- store/
|-------- configureStore.ts/
|---- styles/
|---- assets/
|---- utils/
|---- services/
|---- App.tsx
|---- index.tsx

