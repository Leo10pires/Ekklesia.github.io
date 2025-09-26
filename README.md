# Ekklesia.github.io
export default function HomePage() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800">
      {/* Header */}
      <header className="bg-white shadow-md p-4 flex justify-between items-center">
        <h1 className="text-2xl font-bold text-indigo-700">EKKLESIA 360</h1>
        <nav className="space-x-4">
          <a href="#sobre" className="hover:text-indigo-600">Quem Somos</a>
          <a href="#projetos" className="hover:text-indigo-600">Projetos</a>
          <a href="#parceiros" className="hover:text-indigo-600">Seja Parceiro</a>
          <a href="#transparencia" className="hover:text-indigo-600">Transparência</a>
          <a href="#contato" className="hover:text-indigo-600">Contato</a>
          <button className="bg-indigo-600 text-white px-4 py-2 rounded-lg shadow-md hover:bg-indigo-700">Doe Agora</button>
        </nav>
      </header>

      {/* Hero Section */}
      <section className="bg-indigo-700 text-white py-20 text-center">
        <h2 className="text-4xl font-bold mb-4">Fortalecendo Igrejas, Transformando Comunidades</h2>
        <p className="max-w-2xl mx-auto mb-6">A EKKLESIA 360 apoia igrejas em seus projetos sociais, oferecendo estrutura, capacitação e recursos para ampliar o impacto na sociedade.</p>
        <button className="bg-white text-indigo-700 font-semibold px-6 py-3 rounded-xl shadow-lg hover:bg-gray-100">Apoie esta missão</button>
      </section>

      {/* Quem Somos */}
      <section id="sobre" className="py-16 px-6 text-center">
        <h3 className="text-3xl font-bold text-indigo-700 mb-6">Quem Somos</h3>
        <p className="max-w-3xl mx-auto text-lg">A EKKLESIA 360 é uma ONG sem fins lucrativos que existe para apoiar igrejas e comunidades religiosas em suas atividades sociais e educacionais, ajudando-as a se manterem firmes e atuantes no cuidado com a sociedade.</p>
      </section>

      {/* Projetos */}
      <section id="projetos" className="py-16 bg-gray-100 px-6 text-center">
        <h3 className="text-3xl font-bold text-indigo-700 mb-10">Nossos Projetos</h3>
        <div className="grid md:grid-cols-3 gap-6 max-w-6xl mx-auto">
          <div className="bg-white p-6 rounded-xl shadow-md">
            <h4 className="text-xl font-semibold mb-2">Capacitação de Líderes</h4>
            <p>Treinamentos e cursos de gestão para pastores e líderes religiosos.</p>
          </div>
          <div className="bg-white p-6 rounded-xl shadow-md">
            <h4 className="text-xl font-semibold mb-2">Apoio Social</h4>
            <p>Campanhas de doação de alimentos, roupas e auxílio a famílias carentes.</p>
          </div>
          <div className="bg-white p-6 rounded-xl shadow-md">
            <h4 className="text-xl font-semibold mb-2">Projetos Comunitários</h4>
            <p>Parcerias com igrejas para cursos, palestras e atividades sociais.</p>
          </div>
        </div>
      </section>

      {/* Seja Parceiro */}
      <section id="parceiros" className="py-16 px-6 text-center">
        <h3 className="text-3xl font-bold text-indigo-700 mb-6">Seja Parceiro</h3>
        <p className="max-w-2xl mx-auto mb-6">Empresas, igrejas e pessoas físicas podem apoiar a missão da EKKLESIA 360 por meio de doações, voluntariado ou parcerias institucionais.</p>
        <button className="bg-indigo-600 text-white px-6 py-3 rounded-xl shadow-md hover:bg-indigo-700">Quero ser parceiro</button>
      </section>

      {/* Transparência */}
      <section id="transparencia" className="py-16 bg-gray-100 px-6 text-center">
        <h3 className="text-3xl font-bold text-indigo-700 mb-6">Transparência</h3>
        <p className="max-w-3xl mx-auto mb-6">Prestamos contas com responsabilidade e transparência. Confira nossos relatórios e saiba como cada doação é aplicada.</p>
        <a href="#" className="text-indigo-600 font-semibold hover:underline">Ver Relatórios</a>
      </section>

      {/* Contato */}
      <section id="contato" className="py-16 px-6 text-center">
        <h3 className="text-3xl font-bold text-indigo-700 mb-6">Fale Conosco</h3>
        <p className="max-w-2xl mx-auto mb-6">Entre em contato para saber mais sobre como participar, apoiar ou tirar dúvidas sobre nossa atuação.</p>
        <form className="max-w-lg mx-auto space-y-4">
          <input type="text" placeholder="Seu Nome" className="w-full border rounded-lg p-3" />
          <input type="email" placeholder="Seu E-mail" className="w-full border rounded-lg p-3" />
          <textarea placeholder="Sua Mensagem" rows="4" className="w-full border rounded-lg p-3"></textarea>
          <button type="submit" className="bg-indigo-600 text-white px-6 py-3 rounded-xl shadow-md hover:bg-indigo-700">Enviar</button>
        </form>
      </section>

      {/* Footer */}
      <footer className="bg-indigo-700 text-white text-center p-6">
        <p>&copy; {new Date().getFullYear()} EKKLESIA 360 - Todos os direitos reservados.</p>
      </footer>
    </div>
  );
}
