<div>
    <p>Vimos o que é um flex container e como dispor os elementos dentro deste container utilizando as
        propriedades <code>justify-content</code> e <code>align-items</code>. Vamos adicionar alguns comentários:</p>
    <p>A propriedade <code>display: flex</code> e o flex container:</p>
    <ul>
        <li>Aplicamos a propriedade <code>display: flex</code> no elemento que irá se transformar em um flex container.
        </li>
        <li>Elementos que são flex container podem usar propriedades de disposição de elementos como
            <code>justify-content</code> e <code>align-items</code>.</li>
    </ul>
    <blockquote>
        <p>Importante lembrar que as propriedades <code>justify-content</code> e <code>align-items</code> apenas
            movimentam as tags filhas diretas do flex container.</p>
    </blockquote>
    <p>A propriedade <code>justify-content</code>:</p>
    <ul>
        <li>Adicionamos essa propriedade dentro de um flex container para dispor elementos no seu fluxo horizontal.</li>
        <li>Alguns valores aceitos: <code>flex-start</code> (valor padrão), <code>flex-end</code>, <code>center</code>,
            <code>space-around</code>, <code>space-evenly</code> e <code>space-between</code>.</li>
    </ul>
    <blockquote>
        <p>Tenha em mente que a propriedade movimenta os elementos dentro do flex container simplesmente redistribuindo
            o espaço disponível. Se não existir um espaço vazio dentro do flex container, essa propriedade não vai ter
            efeito.</p>
        <p>Isso acontece principalmente quando os conteúdos dos elementos excedem as dimensões do flex container.</p>
        <p>Como essa propriedade trabalha apenas com a redistribuição do espaço restante, ela não permite o controle
            preciso da distância entre elementos. Para um espaçamento mais preciso, é necessário utilizar as
            propriedades <code>margin</code> ou <code>padding</code> ou as duas no elemento específico que você precisa
            espaçar.</p>
    </blockquote>
    <p>A propriedade <code>align-items</code>:</p>
    <ul>
        <li>Adicionamos essa propriedade dentro de um flex container para trabalhar com o alinhamento vertical dos
            elementos.</li>
        <li>Alguns valores aceitos: <code>flex-start</code>, <code>flex-end</code>, <code>center</code> e
            <code>stretch</code> (valor padrão).</li>
    </ul>
</div>