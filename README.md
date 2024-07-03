<?php

class SobreMim {
    private $formacao;
    private $atuacaoAtual;
    private $tecnologias;
    private $sentimentoTrabalho;
    private $motivacao;
    private $filosofia;
    private $contatos;

    public function __construct() {
        $this->formacao = "Engenheiro Mecânico";
        $this->atuacaoAtual = "Desenvolvedor Full Stack";
        $this->tecnologias = ["Laravel", "PHP", "Node.js", "JavaScript", "TypeScript", "PostgreSQL", "MySQL", "MongoDB"];
        $this->sentimentoTrabalho = "incrível, divertido e recompensador, mesmo com os bugs!";
        $this->motivacao = "desafios e da incessante busca por conhecimento";
        $this->filosofia = "base sólida em lógica de programação e orientação a objetos";
        $this->contatos = [
            'linkedin' => "https://www.linkedin.com/in/vinicius-rcampos/",
            'email' => "vinicius_uo@hotmail.com"
        ];
    }

    public function descricaoFormacao() {
        echo "Formação: " . $this->formacao . "\n";
    }

    public function descricaoAtuacaoAtual() {
        echo "Atuação Atual: " . $this->atuacaoAtual . "\n";
        echo "Tecnologias: " . implode(", ", $this->tecnologias) . "\n";
    }

    public function sentimentoTrabalho() {
        echo "Trabalhar com tecnologia é " . $this->sentimentoTrabalho . ".\n";
        echo "Estar por trás de tantas linhas de código, entender como elas funcionam e se conectam é fascinante.\n";
        echo "Até mesmo quando o código quebra.\n";
    }

    public function motivacaoDiaria() {
        echo "Cada projeto, cada solução sempre vem acompanhado de " . $this->motivacao . ".\n";
        echo "Aprender algo novo constantemente é o que me motiva e mantém minha paixão pelo desenvolvimento.\n";
    }

    public function filosofiaTrabalho() {
        echo "Acredito firmemente que a base para o sucesso é uma " . $this->filosofia . ".\n";
        echo "Uma estrutura bem planejada e robusta não só facilita a resolução de problemas complexos, mas também traz agilidade para refatorar o projeto.\n";
    }

    public function contato() {
        echo "Se conecte comigo no LinkedIn: " . $this->contatos['linkedin'] . "!\n";
        echo "Meu melhor email é: " . $this->contatos['email'] . "!\n";
    }

    public function sobreMim() {
        $this->descricaoFormacao();
        $this->descricaoAtuacaoAtual();
        $this->sentimentoTrabalho();
        $this->motivacaoDiaria();
        $this->filosofiaTrabalho();
        $this->contato();
        echo "Se até para aprender a andar eu caí, por que não posso tropeçar em códigos?\n";
    }
}

$perfil = new SobreMim();
$perfil->sobreMim();

?>
- 📫 Meus principais links para contatos:
- :link: https://www.linkedin.com/in/vinicius-rcampos/
- :envelope:vinicius_uo@hotmail.com

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=viniciusrcampos&show_icons=true&theme=radical)


