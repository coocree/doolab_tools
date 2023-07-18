# Componente simuc_info
Este é um README para o componente simuc_info, um componente de interface com o usuário que exibe a barra de status em uma aplicação.

## Sobre o simuc_info
O componente simuc_info é uma parte crítica de muitas interfaces de usuário. Ele pode exibir informações como o status de uma operação em andamento, o nível atual de progresso de uma tarefa, uma mensagem de status ou outras informações importantes que os usuários precisam conhecer.

### Como usar o componente simuc_info
Para usar o simuc_info, você precisa importá-lo em seu arquivo de componente e inseri-lo em sua renderização de JSX. Por exemplo:

```dart
import simuc_info from './listswitch';

function App() {
  return (
    <div className="App">
      <listswitch status="Carregando..." progress={75}/>
    </div>
  );
}

export default App;
```
