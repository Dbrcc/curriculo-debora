import React from "react";

export default function CurriculoDebora() {
  return (
    <div className="max-w-4xl mx-auto p-6 text-gray-800">
      <h1 className="text-4xl font-bold mb-4">DÉBORA CONCEIÇÃO DA SILVA</h1>
      <p className="mb-2">📞 (21) 9 7674-8610</p>
      <p className="mb-2">📧 pontessilva123@gmail.com</p>
      <p className="mb-6">📍 Rua Antonio Noel, Petrópolis - RJ</p>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">Sobre Mim</h2>
        <p>
          Profissional proativa e dedicada, com experiência em atendimento ao cliente e habilidades sólidas em comunicação,
          resolução de problemas e organização. Tenho facilidade de aprendizado, busco aplicar meus conhecimentos para
          garantir a satisfação dos clientes e contribuir positivamente para o crescimento da equipe. Disponível para
          horários flexíveis, com facilidade no uso de ferramentas digitais e boa adaptação a ambientes de trabalho remotos e presenciais.
        </p>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">Experiência Profissional</h2>

        <div className="mb-4">
          <h3 className="font-bold">Hospital Santa Teresa | Técnica de Enfermagem (2025 – Atual)</h3>
          <ul className="list-disc list-inside ml-4">
            <li>Prestei assistência humanizada e personalizada aos pacientes.</li>
            <li>Realizei anotações de enfermagem detalhadas, promovendo rastreabilidade e precisão clínica.</li>
            <li>Monitorei sinais vitais e acompanhei tratamentos com foco em protocolos de segurança.</li>
            <li>Colaborei com a equipe multiprofissional em ações educativas e rotinas assistenciais.</li>
          </ul>
        </div>

        <div className="mb-4">
          <h3 className="font-bold">Hospital Notre Care | Técnica de Enfermagem - Unidade de Internação (Abr/2022 – Jul/2025)</h3>
          <ul className="list-disc list-inside ml-4">
            <li>Prestei cuidados diretos aos pacientes, garantindo conforto e bem-estar.</li>
            <li>Registrei prontuários com precisão e participei de reuniões de equipe.</li>
            <li>Assisti em procedimentos médicos e higienização de materiais.</li>
            <li>Atuei no controle de estoque e organização da unidade de internação.</li>
          </ul>
        </div>

        <div>
          <h3 className="font-bold">Faculdade UNIG | Atendente de Cliente (Mar/2019 – Ago/2020)</h3>
          <ul className="list-disc list-inside ml-4">
            <li>Realizei atendimento presencial e telefônico, auxiliando estudantes com orientações acadêmicas.</li>
            <li>Atualizei cadastros e organizei arquivos de alunos e visitantes.</li>
            <li>Gerenciei demandas administrativas e encaminhei solicitações para os setores competentes.</li>
            <li>Desenvolvi escuta ativa e abordagem cordial para aprimorar a experiência do usuário.</li>
          </ul>
        </div>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">Formação</h2>
        <ul className="list-disc list-inside ml-4">
          <li>Segurança no Trabalho | Universidade Costa Verde – Cursando (2025)</li>
          <li>Farmácia | Universidade Cruzeiro do Sul – Cursando (2025)</li>
          <li>Ocupações Administrativas (CBO) | CIEE – 1280 horas – Concluído (2021)</li>
          <li>Técnico de Enfermagem | Cruz Vermelha Brasileira – Concluído (2020)</li>
          <li>Ensino Médio | CIEP 324 Mahatma Gandhi – Concluído (2019)</li>
        </ul>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-2">Certificações</h2>
        <ul className="list-disc list-inside ml-4">
          <li>Pacote Office Intermediário | Bradesco (2024)</li>
          <li>Comunicação Não Violenta | Hospital Santa Teresa (2024)</li>
          <li>Atendimento Pré-Hospitalar | Faculdade UNIFTB (2024)</li>
          <li>Procedimentos Técnicos em UTI | Faculdade UNIFTB (2024)</li>
          <li>Urgência e Emergência | Faculdade UNIFTB (2024)</li>
          <li>Emergências Cardiológicas | Cruz Vermelha Brasileira (2020)</li>
          <li>Suporte Básico de Vida | Cruz Vermelha Brasileira (2019)</li>
          <li>Tratamento de Feridas e Curativos | Faculdade UNIFTB (2019)</li>
          <li>Central de Material e Esterilização (CME) | Faculdade UNIFTB (2025)</li>
        </ul>
      </section>
    </div>
  );
}
