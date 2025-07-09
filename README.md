<p align="center">
  <img src="https://s3-eu-west-1.amazonaws.com/tpd/logos/5ed64c639792a000014303ca/0x0.png" alt="Logo" />
</p>

<h2>🚀 Installation / Kurulum</h2>

<h3>📦 Google Tag Manager Entegrasyonu</h3>

<h4>🇹🇷 Türkçe</h4>

<ol>
  <li>Google Tag Manager’a giriş yapın.</li>
  <li>Sol menüden “<strong>Etiketler</strong>” bölümüne gidin.</li>
  <li><strong>Yeni Etiket</strong> oluşturun.</li>
  <li>Etiket tipi olarak <strong>Custom HTML</strong> seçin üstteki Custom.js içerisindeki kodu kopyalayıp yapıştırın.</li>
  <li>Trigger olarak şu koşulu ayarlayın: <code>All Pages</code></li>
  <li><code>dataLayer</code> içindeki <code>inputs</code> objesi sayesinde form verilerine ulaşabilirsiniz.</li>
  <li>Etiketi kaydedin ve yayına alın.</li>
</ol>

<h4>🇬🇧 English</h4>

<ol>
  <li>Log in to Google Tag Manager dashboard.</li>
  <li>Go to the <strong>Tags</strong> section.</li>
  <li>Create a <strong>New Tag</strong>.</li>
  <li>Set tag type as <strong>Custom HTML</strong> Copy and paste the code in Custom.js above..</li>
  <li>Set a trigger with condition: <code>All Pages</code></li>
  <li>You can access submitted form data via the <code>inputs</code> object in <code>dataLayer</code>.</li>
  <li>Save and publish the container.</li>
</ol>

<h3>✅ Sonuç / Result</h3>

<p>
  WPForms ile gönderilen tüm form verileri <code>dataLayer</code> içine otomatik olarak gönderilir. 
  Bu sayede Google Analytics, Facebook Pixel ve diğer pazarlama araçlarına kolayca iletim sağlanır.
</p>
