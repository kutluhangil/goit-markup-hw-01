<h1>📸 Focus.Frame — Single-Page Photography Website</h1>

<p><em>Discover the magic of photography in our school!</em></p>

<p>
  <strong>Focus.Frame</strong>, GoIT Full Stack Developer kursu kapsamında geliştirilen,
  tek sayfalık ve tamamen responsive bir fotoğrafçılık okulu websitesidir.
  Sayfa; kurslar, mentorlar, yorumlar, iletişim ve profesyonel bir footer bölümü içerir.
</p>

<hr />

<h2>🌐 Live Demo</h2>
<p>
  👉 <a href="https://kutluhangil.github.io/goit-focusframe-project/" target="_blank" rel="noopener">Focus Frame Linki</a>
</p>

<hr />

<h2>📋 Table of Contents</h2>
<ol>
  <li><a href="#about-the-project">About the Project</a></li>
  <li><a href="#core-features-and-requirements">Core Features &amp; Requirements</a></li>
  <li><a href="#technical-specifications">Technical Specifications</a></li>
  <li><a href="#project-structure-sections">Project Structure (Sections)</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#technologies-used">Technologies Used</a></li>
  <li><a href="#team-members">Team Members</a></li>
  <li><a href="#challenges">Challenges</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><a href="#license">License</a></li>
</ol>

<hr />

<h2 id="about-the-project">📖 About the Project</h2>
<p>
  Focus.Frame, gerçek bir landing page deneyimini simüle eder:
</p>
<ul>
  <li>Okulu tanıtan bir <strong>Hero</strong> alanı</li>
  <li><strong>Kurs</strong> kartları (Basics, Landscape, Portrait)</li>
  <li><strong>Mentor</strong> profilleri</li>
  <li>Öğrenci <strong>Reviews</strong></li>
  <li><strong>Sign Up</strong> formu</li>
  <li>Sosyal bağlantılar ve iletişim bilgilerinin bulunduğu <strong>Footer</strong></li>
</ul>

<hr />

<h2 id="core-features-and-requirements">✨ Core Features and Requirements</h2>

<h3>Layout and Responsiveness 📱💻🖥️</h3>
<ul>
  <li><strong>Mobile:</strong> 375px ve üzeri</li>
  <li><strong>Tablet:</strong> 768px ve üzeri</li>
  <li><strong>Desktop:</strong> 1280px ve üzeri (isteğe bağlı 1440px optimizasyonu)</li>
</ul>

<hr />

<h2 id="technical-specifications">⚙️ Technical Specifications</h2>
<ul>
  <li><strong>Validation:</strong> HTML/CSS doğrulamalarını geçmelidir:
    <ul>
      <li><a href="https://validator.w3.org/" target="_blank" rel="noopener">validator.w3.org</a></li>
      <li><a href="https://jigsaw.w3.org/css-validator/" target="_blank" rel="noopener">jigsaw.w3.org/css-validator</a></li>
      <li><a href="https://pagespeed.web.dev/" target="_blank" rel="noopener">pagespeed.web.dev</a></li>
    </ul>
  </li>
  <li><strong>Semantics:</strong> HTML5 semantik etiketleri ile uyum</li>
  <li><strong>Fonts:</strong> Harici bağlantı ile yüklenmeli</li>
  <li><strong>Image Optimization:</strong>
    <ul>
      <li>Vektör/raster görseller için optimize boyutlar</li>
      <li>Retina ekran desteği</li>
      <li>Yükleme optimizasyonu (boyut/sıkıştırma)</li>
    </ul>
  </li>
  <li><strong>SVG Icons:</strong> Tüm ikonlar <code>sprite</code> üzerinden bağlanmalı</li>
  <li><strong>Favicon:</strong> Sayfa için favicon görseli eklenmeli</li>
</ul>

<hr />

<h2 id="project-structure-sections">🏗️ Project Structure (Sections)</h2>

<ul>
  <li><strong>Header:</strong> Logo, navigasyon, “Sign Up” bağlantısı (mobile’da kamera ikonu). Mobile menü viewport yüksekliğine sabit <em>dropdown sidebar</em>. Header ve Hero, ortak <em>dotted grid</em> arka plan PNG’ini saran bir wrapper ile uygulanır.</li>
  <li><strong>Hero:</strong> Başlık: “Discover the magic of photography in our school.” Metin, öğrenci/refs bloğu. “Our happy students” linki Reviews bölümüne götürür.</li>
  <li><strong>Advertisement:</strong> Başlık tek satır: “Master your photography skills with us!”</li>
  <li><strong>About Us:</strong> Başlık “About us.” İçerik görselleri <em>content image</em> olarak eklenir.</li>
  <li><strong>Our Courses:</strong> Başlık “Our courses.” Liste <code>&lt;ol&gt;</code> ile numaralıdır. Kart: numara + başlık + açıklama + ⇗ link ikonu (tıklandığında <em>Sign Up</em> bölümüne gider).</li>
  <li><strong>Our Mentors:</strong> Başlık “Our Mentors.” Liste <code>&lt;ul&gt;</code>. Kart: fotoğraf (content image) + isim + deneyim.</li>
  <li><strong>Sign Up:</strong> Başlık “Sign up.” Formda <code>&lt;input pattern&gt;</code>, <code>&lt;textarea&gt;</code> ve <code>type="submit"</code> “Send” butonu bulunur.</li>
  <li><strong>Reviews:</strong> Başlık “Reviews.” Liste <code>&lt;ul&gt;</code>. Kart: fotoğraf + isim + statü + geri bildirim + rating.</li>
  <li><strong>Footer:</strong> Logo, iletişim bilgileri, sosyal bağlantılar listesi, site linkleri listesi, <code>required</code> ve <code>pattern</code> içeren input + “Go” butonu.
    <ul>
      <li>Telefon numarası <strong>link protokolü</strong> ile (<code>tel:</code>)</li>
      <li>Sosyal linkler <code>&lt;ul&gt;</code> ile ve yeni sekmede açılır:
        <ul>
          <li><a href="https://www.instagram.com/goit.turkiye/" target="_blank" rel="noopener">Instagram</a></li>
          <li><a href="https://m.youtube.com/@GoITTurkey" target="_blank" rel="noopener">YouTube</a></li>
          <li><a href="https://www.facebook.com/people/GOIT-T%C3%BCrkiye/61558036560161/" target="_blank" rel="noopener">Facebook</a></li>
        </ul>
      </li>
      <li><em>Dotted grid</em> görseli arka plan PNG olarak uygulanır.</li>
    </ul>
  </li>
</ul>

<hr />

<h2 id="features">💡 Features</h2>
<ul>
  <li>Tamamen <strong>responsive</strong> (mobile–tablet–desktop)</li>
  <li><strong>Flexbox</strong> &amp; <strong>CSS Grid</strong> ile layout</li>
  <li>Semantik HTML iskeleti</li>
  <li>Figma tasarımına uygun modern tipografi ve UI</li>
  <li>Footer’da şirket bilgileri, hızlı linkler, abonelik formu</li>
</ul>

<hr />

<h2 id="technologies-used">🛠️ Technologies Used</h2>
<ul>
  <li><strong>HTML5</strong> — Semantik yapı</li>
  <li><strong>CSS3</strong> — Stil &amp; responsive düzen</li>
  <li><strong>Flexbox &amp; CSS Grid</strong> — Mizanpaj</li>
  <li><strong>Git &amp; GitHub</strong> — Versiyon kontrol &amp; iş birliği</li>
  <li><strong>Figma</strong> — Tasarım referansı</li>
</ul>

<hr />

<h2 id="team-members">👥 Team Members</h2>
<p>GoIT grup projesi kapsamında geliştirilmiştir.</p>
<ul>
  <li><strong>Kutluhan Gül</strong> — Footer section</li>
  <li>(Diğer takım üyelerini ve sorumluluklarını ekleyin)</li>
</ul>
<p>Çalışma şekli: GitHub branch’leri, Pull Request’ler, Trello/issue takibi.</p>

<hr />

<h2 id="challenges">🚧 Challenges</h2>
<ul>
  <li>Figma ile <strong>pixel-perfect</strong> uyum</li>
  <li>Tüm kırılım noktalarında <strong>responsive</strong> davranış</li>
  <li>Font, boşluk ve ikon hizalarının kararlı tutulması</li>
  <li>Takım koordinasyonu, merge çatışmalarının çözümü</li>
</ul>

<hr />

<h2 id="screenshots">📸 Screenshots</h2>
<p>
  <img src="./FocusFrame-1440.jpeg" alt="Focus.Frame - 1440px Desktop Preview" width="100%" />
</p>

<hr />

<h2 id="license">📜 License</h2>
<p>
  This project is created for <strong>educational purposes</strong> under the GoIT Full Stack Developer course.
  <br />© 2024 Focus.Frame — All rights reserved
</p>
