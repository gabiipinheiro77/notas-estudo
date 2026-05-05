//Não usar ESPAÇO, ACENTO,Ç,!@#$%¨&*

// Number é uma função que tenta converter

//um valor passado para número

Vite é o ajudante: É a ferramenta que monta a estrutura do projeto rápido.

App.jsx: É o "chef" da cozinha, onde tu montas o prato principal.

main.jsx: É quem serve o prato, ligando o React ao HTML real do navegador.

Assets vs Public: Assets: Coisas que o sistema precisa processar tipo fotos que tu usas no código.

Public: Ficheiros que ficam lá parados, sem ninguém mexer (ipo o ícone que aparece na aba do navegador.

Props Passar a bola: É como tu passas informação de um componente para outro. Exemplo: Tu crias um componente de "Cartão" e passas o nome do produto via Props. Assim, o mesmo "Cartão" serve para 50 produtos diferentes.

Virtual DOM: O React é rápido porque ele tem uma "cópia" da página na memória. Ele só mexe no site de verdade quando algo realmente mudou. Isso evita que o navegador fique lento.

Criar o projeto: npm create vite@latest .

No terminal: npm i react-router-dom

O que é: Um Hook que dá "memória" ao componente. Se o valor muda, o React renderiza a tela de novo.

Sintaxe: const [valor, setValor] = useState(inicial).

valor: É onde a informação está guardada agora.

setValor: É a única função que você pode usar para mudar esse valor.

Formulários: O slide mostra que usamos o e.target.value dentro de um evento (como onChange) para capturar o que o usuário digita e salvar no estado.

useEffect (O Controlador de Efeitos)
Serve para lidar com coisas que acontecem fora do fluxo normal do React (efeitos colaterais).

O Array de Dependências []:

Vazio []: O código roda só uma vez, quando o componente aparece na tela (montagem).

Com variável [nome]: O código roda toda vez que o valor de nome mudar.

Sem array: O código roda em toda e qualquer atualização do componente (cuidado, pode travar o navegador).

eventos e e.target

e.target: O elemento que sofreu a ação (ex: o campo de input).

e.target.name: O nome do campo (útil para formulários com vários campos).

e.target.value: O conteúdo que está escrito no campo naquele momento.