# REACT + REDUX + TYPESCRIPT 2021
npx create-react-app . --template typescript 

npm install @types/react-redux redux react-redux redux-thunk axios

## типы
типы описываются в интерфейсах, а потом интерфейы указываются через двоеточие в initialState:

interface UserState {
    users: any[];
    loading: boolean;
    error: null | string;

}

const initialState: UserState = {
    users: [],
    loading: false,
    error: null
}

## ctrl + space для того, чтобы увидеть выпадающий автокомплит TS 
24:15
