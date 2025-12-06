class D3TwinsViewer extends HTMLElement {
  constructor() {
    super();
    this.attachShadow({ mode: "closed" });

    const wrapper = document.createElement("div");
    wrapper.style.width = "100%";
    wrapper.style.height = "100%";
    wrapper.style.position = "relative";
    wrapper.style.background = "black";

    this.iframe = document.createElement("iframe");
    this.iframe.style.width = "100%";
    this.iframe.style.height = "100%";
    this.iframe.style.border = "none";
    this.iframe.allow = "xr-spatial-tracking; fullscreen";

    wrapper.appendChild(this.iframe);
    this.shadowRoot.appendChild(wrapper);
  }

  connectedCallback() {
    // ➤ Recibimos la URL cruda desde el iframe
    const raw = this.getAttribute("src");
    if (!raw) {
      console.error("❌ WebComponent sin URL en atributo src");
      return;
    }

    // ➤ Extraer solo el query string (?token=ALIEN)
    const queryIndex = raw.indexOf("?");
    const qs = queryIndex !== -1 ? raw.slice(queryIndex) : "";

    // ➤ NUEVA BASE del visor real
    const viewerBase = "https://load.3dtwins.tech/index2.html";

    // ➤ Construir la URL final SIN tocar el token ALIEN
    this.iframe.src = viewerBase + qs;
  }
}

customElements.define("d3-twins-viewer", D3TwinsViewer);
