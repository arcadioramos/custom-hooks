# custom-hooks
Custom hooks
Ejemplo :
const initialForm = {
  name: '',
  age: 0,
  email: '',
};
//Obligatorio poner el name en el input para reconocer el valor
const [formValues, handleInputChange, reset] = useForm(initialForm);
