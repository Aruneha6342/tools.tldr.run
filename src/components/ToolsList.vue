<template>
  <div>
    <section class="hero is-bold">
      <div class="container hero-body">
        <h1 class="title is-1 has-text-centered has-text-white">
          Security Tools!
        </h1>
        <h2 class="subtitle has-text-centered has-text-white">
          Curated list of security tools for Hackers & Builders!
        </h2>

        <h2 class="title is-5 has-text-centered">
          <a
            class="button has-text-dark has-background-light"
            href="https://github.com/tldrrun/tools.tldr.run#contributing"
            target="_blank"
            >Submit your awesome tools 👍</a
          >
        </h2>

        <center>
          <a
            href="https://twitter.com/tldrrun?ref_src=twsrc%5Etfw"
            class="twitter-follow-button"
            data-size="large"
            data-dnt="true"
            data-show-count="true"
            >Follow @tldrrun</a
          >
        </center>

        <div class="has-text-centered">
          <!-- Sharingbutton Facebook -->
          <a
            class="resp-sharing-button__link"
            href="https://facebook.com/sharer/sharer.php?u=https%3A%2F%2Ftools.tldr.run"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--facebook resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M18.77 7.46H14.5v-1.9c0-.9.6-1.1 1-1.1h3V.5h-4.33C10.24.5 9.5 3.44 9.5 5.32v2.15h-3v4h3v12h5v-12h3.85l.42-4z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton Twitter -->
          <a
            class="resp-sharing-button__link"
            href="https://twitter.com/intent/tweet/?text=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!&amp;url=https%3A%2F%2Ftools.tldr.run"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--twitter resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M23.44 4.83c-.8.37-1.5.38-2.22.02.93-.56.98-.96 1.32-2.02-.88.52-1.86.9-2.9 1.1-.82-.88-2-1.43-3.3-1.43-2.5 0-4.55 2.04-4.55 4.54 0 .36.03.7.1 1.04-3.77-.2-7.12-2-9.36-4.75-.4.67-.6 1.45-.6 2.3 0 1.56.8 2.95 2 3.77-.74-.03-1.44-.23-2.05-.57v.06c0 2.2 1.56 4.03 3.64 4.44-.67.2-1.37.2-2.06.08.58 1.8 2.26 3.12 4.25 3.16C5.78 18.1 3.37 18.74 1 18.46c2 1.3 4.4 2.04 6.97 2.04 8.35 0 12.92-6.92 12.92-12.93 0-.2 0-.4-.02-.6.9-.63 1.96-1.22 2.56-2.14z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton LinkedIn -->
          <a
            class="resp-sharing-button__link"
            href="https://www.linkedin.com/shareArticle?mini=true&amp;url=https%3A%2F%2Ftools.tldr.run&amp;title=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!&amp;summary=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!&amp;source=https%3A%2F%2Ftools.tldr.run"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--linkedin resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M6.5 21.5h-5v-13h5v13zM4 6.5C2.5 6.5 1.5 5.3 1.5 4s1-2.4 2.5-2.4c1.6 0 2.5 1 2.6 2.5 0 1.4-1 2.5-2.6 2.5zm11.5 6c-1 0-2 1-2 2v7h-5v-13h5V10s1.6-1.5 4-1.5c3 0 5 2.2 5 6.3v6.7h-5v-7c0-1-1-2-2-2z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton Reddit -->
          <a
            class="resp-sharing-button__link"
            href="https://reddit.com/submit/?url=https%3A%2F%2Ftools.tldr.run&amp;resubmit=true&amp;title=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--reddit resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M24 11.5c0-1.65-1.35-3-3-3-.96 0-1.86.48-2.42 1.24-1.64-1-3.75-1.64-6.07-1.72.08-1.1.4-3.05 1.52-3.7.72-.4 1.73-.24 3 .5C17.2 6.3 18.46 7.5 20 7.5c1.65 0 3-1.35 3-3s-1.35-3-3-3c-1.38 0-2.54.94-2.88 2.22-1.43-.72-2.64-.8-3.6-.25-1.64.94-1.95 3.47-2 4.55-2.33.08-4.45.7-6.1 1.72C4.86 8.98 3.96 8.5 3 8.5c-1.65 0-3 1.35-3 3 0 1.32.84 2.44 2.05 2.84-.03.22-.05.44-.05.66 0 3.86 4.5 7 10 7s10-3.14 10-7c0-.22-.02-.44-.05-.66 1.2-.4 2.05-1.54 2.05-2.84zM2.3 13.37C1.5 13.07 1 12.35 1 11.5c0-1.1.9-2 2-2 .64 0 1.22.32 1.6.82-1.1.85-1.92 1.9-2.3 3.05zm3.7.13c0-1.1.9-2 2-2s2 .9 2 2-.9 2-2 2-2-.9-2-2zm9.8 4.8c-1.08.63-2.42.96-3.8.96-1.4 0-2.74-.34-3.8-.95-.24-.13-.32-.44-.2-.68.15-.24.46-.32.7-.18 1.83 1.06 4.76 1.06 6.6 0 .23-.13.53-.05.67.2.14.23.06.54-.18.67zm.2-2.8c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zm5.7-2.13c-.38-1.16-1.2-2.2-2.3-3.05.38-.5.97-.82 1.6-.82 1.1 0 2 .9 2 2 0 .84-.53 1.57-1.3 1.87z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton WhatsApp -->
          <a
            class="resp-sharing-button__link"
            href="whatsapp://send?text=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!%20https%3A%2F%2Ftools.tldr.run"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--whatsapp resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M20.1 3.9C17.9 1.7 15 .5 12 .5 5.8.5.7 5.6.7 11.9c0 2 .5 3.9 1.5 5.6L.6 23.4l6-1.6c1.6.9 3.5 1.3 5.4 1.3 6.3 0 11.4-5.1 11.4-11.4-.1-2.8-1.2-5.7-3.3-7.8zM12 21.4c-1.7 0-3.3-.5-4.8-1.3l-.4-.2-3.5 1 1-3.4L4 17c-1-1.5-1.4-3.2-1.4-5.1 0-5.2 4.2-9.4 9.4-9.4 2.5 0 4.9 1 6.7 2.8 1.8 1.8 2.8 4.2 2.8 6.7-.1 5.2-4.3 9.4-9.5 9.4zm5.1-7.1c-.3-.1-1.7-.9-1.9-1-.3-.1-.5-.1-.7.1-.2.3-.8 1-.9 1.1-.2.2-.3.2-.6.1s-1.2-.5-2.3-1.4c-.9-.8-1.4-1.7-1.6-2-.2-.3 0-.5.1-.6s.3-.3.4-.5c.2-.1.3-.3.4-.5.1-.2 0-.4 0-.5C10 9 9.3 7.6 9 7c-.1-.4-.4-.3-.5-.3h-.6s-.4.1-.7.3c-.3.3-1 1-1 2.4s1 2.8 1.1 3c.1.2 2 3.1 4.9 4.3.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.6-.1 1.7-.7 1.9-1.3.2-.7.2-1.2.2-1.3-.1-.3-.3-.4-.6-.5z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton Hacker News -->
          <a
            class="resp-sharing-button__link"
            href="https://news.ycombinator.com/submitlink?u=https%3A%2F%2Ftools.tldr.run&amp;t=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--hackernews resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 140 140">
                  <path
                    fill-rule="evenodd"
                    d="M60.94 82.314L17 0h20.08l25.85 52.093c.397.927.86 1.888 1.39 2.883.53.994.995 2.02 1.393 3.08.265.4.463.764.596 1.095.13.334.262.63.395.898.662 1.325 1.26 2.618 1.79 3.877.53 1.26.993 2.42 1.39 3.48 1.06-2.254 2.22-4.673 3.48-7.258 1.26-2.585 2.552-5.27 3.877-8.052L103.49 0h18.69L77.84 83.308v53.087h-16.9v-54.08z"
                  />
                </svg>
              </div>
            </div>
          </a>

          <!-- Sharingbutton Telegram -->
          <a
            class="resp-sharing-button__link"
            href="https://telegram.me/share/url?text=Curated%20list%20of%20security%20tools%20for%20Hackers%20%26%20Builders!&amp;url=https%3A%2F%2Ftools.tldr.run"
            target="_blank"
            rel="noopener"
            aria-label
          >
            <div
              class="resp-sharing-button resp-sharing-button--telegram resp-sharing-button--small"
            >
              <div
                aria-hidden="true"
                class="resp-sharing-button__icon resp-sharing-button__icon--solid"
              >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                  <path
                    d="M.707 8.475C.275 8.64 0 9.508 0 9.508s.284.867.718 1.03l5.09 1.897 1.986 6.38a1.102 1.102 0 0 0 1.75.527l2.96-2.41a.405.405 0 0 1 .494-.013l5.34 3.87a1.1 1.1 0 0 0 1.046.135 1.1 1.1 0 0 0 .682-.803l3.91-18.795A1.102 1.102 0 0 0 22.5.075L.706 8.475z"
                  />
                </svg>
              </div>
            </div>
          </a>
        </div>

        <br />
        <div class="field has-addons" ref="input">
          <span class="showOpenSidebar" v-on:click="openSidebar">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-menu"
            >
              <line x1="3" y1="12" x2="21" y2="12"></line>
              <line x1="3" y1="6" x2="21" y2="6"></line>
              <line x1="3" y1="18" x2="21" y2="18"></line>
            </svg>
          </span>
          <!-- v-model="search" -->
          <input
            class="input is-rounded"
            type="text"
            placeholder="Search Here"
            v-on:input="setSearchTerm"
          />
        </div>
      </div>
    </section>

    <section class="filterBar">
      <label
        class="column checkbox"
        :class="{ active: selectedOS.includes('windows') }"
      >
        <input type="checkbox" value="windows" v-model="selectedOS" />
        <Windows />Windows
      </label>
      <label
        class="column checkbox"
        :class="{ active: selectedOS.includes('linux') }"
      >
        <input type="checkbox" value="linux" v-model="selectedOS" />
        <Linux />Linux
      </label>
      <label
        class="column checkbox"
        :class="{ active: selectedOS.includes('mac') }"
      >
        <input type="checkbox" value="mac" v-model="selectedOS" />
        <Mac />Mac OSX
      </label>
      <label
        class="column checkbox"
        :class="{ active: selectedAvailability.includes('opensource') }"
      >
        <input
          type="checkbox"
          value="opensource"
          v-model="selectedAvailability"
        />
        <OpenSource />Open Source
      </label>
      <label
        class="column checkbox"
        :class="{ active: selectedAvailability.includes('free') }"
      >
        <input type="checkbox" value="free" v-model="selectedAvailability" />
        <CoffeeCup />Free
      </label>
      <label
        class="column checkbox"
        :class="{ active: selectedAvailability.includes('commercial') }"
      >
        <input
          type="checkbox"
          value="commercial"
          v-model="selectedAvailability"
        />
        <Dollar />Commercial
      </label>
    </section>

    <section class="section body">
      <Tags
        :tagsList="tags"
        :selectedTags="selectedTags"
        v-on:selectTag="selectTag"
        v-on:clearTagSelection="clearTagSelection"
        v-on:closeSidebar="closeSidebar"
        class="tabsList"
        :class="{ open: showSidebar }"
      />
      <div class="cardContainer" v-if="filteredList.length > 0">
        <div class="card" v-for="tool in filteredList" v-bind:key="tool.name">
          <header class="card-header">
            <div class="card-header-icon" aria-label="more options">
              <span
                class="icon"
                v-if="tool.availability.includes('opensource')"
                title="Open Source"
              >
                <OpenSource />
              </span>
              <span
                class="icon"
                v-if="tool.availability.includes('free')"
                title="Free"
              >
                <CoffeeCup />
              </span>
              <span
                class="icon"
                v-if="tool.availability.includes('commercial')"
                title="Commercial"
              >
                <Dollar />
              </span>
            </div>
            <p class="card-header-title is-centered" style="overflow: auto;">
              <a
                v-bind:href="tool.url"
                target="_blank"
                v-on:click="triggerOpenTool(tool.name)"
                >{{ tool.name }}</a
              >
            </p>
            <div class="card-header-icon" aria-label="more options">
              <span
                class="icon"
                v-if="tool.operating_systems.includes('windows')"
                title="Windows"
              >
                <Windows />
              </span>
              <span
                class="icon"
                v-if="tool.operating_systems.includes('linux')"
                title="Linux"
              >
                <Linux />
              </span>
              <span
                class="icon"
                v-if="tool.operating_systems.includes('mac')"
                title="Mac"
              >
                <Mac />
              </span>
            </div>
          </header>
          <div class="card-content" style="max-height: 200px; overflow: auto;">
            <div class="content has-text-centered">{{ tool.description }}</div>
          </div>
          <footer class="card-footer tags card-footer-item">
            <span class="tag" v-for="tag in tool.tags" v-bind:key="tag">{{
              tag
            }}</span>
          </footer>
        </div>
      </div>
      <div v-if="filteredList.length === 0">
        <h2 class="title is-2 has-text-white has-text-centered">
          No tools found as per your filter
        </h2>
      </div>
    </section>
    <div
      class="scrollToTop"
      v-on:click="scrollToTop"
      v-bind:class="{ top: isTop }"
    >
      ↑
    </div>
  </div>
</template>

<script>
import Tags from "./Tags";
import CoffeeCup from "../icons/coffee-cup";
import Dollar from "../icons/dollar-icon";
import Linux from "../icons/linux-logo";
import Mac from "../icons/mac-logo";
import OpenSource from "../icons/open-source";
import Windows from "../icons/windows-logo";
import Fuse from "fuse.js";
import debounce from "lodash.debounce";

export default {
  name: "Header",
  props: ["toolsData"],
  components: {
    Tags,
    CoffeeCup,
    Dollar,
    Linux,
    Mac,
    OpenSource,
    Windows,
  },
  data() {
    return {
      search: "",
      selectedOS: [],
      selectedAvailability: [],
      selectedTags: [],
      isTop: true,
      showSidebar: false,
      fuse: null,
    };
  },
  computed: {
    tags() {
      const toolsList = this.toolsData.map((tools) => tools.tags).flat();
      return Array.from(new Set(toolsList));
    },
    filteredList() {
      const toolsData =
        this.search === ""
          ? this.toolsData
          : this.fuse.search(this.search).map((toolsObj) => toolsObj.item);

      const returnData = toolsData
        .filter((tools) => {
          if (this.selectedOS.length == 0) {
            return true;
          }
          let osPresent = false;
          this.selectedOS.forEach((operating_systems) => {
            if (tools.operating_systems.includes(operating_systems)) {
              osPresent = true;
            }
          });
          return osPresent;
        })
        .filter((tools) => {
          if (this.selectedAvailability.length == 0) {
            return true;
          }
          let availabilityPresent = false;
          this.selectedAvailability.forEach((availability) => {
            if (tools.availability.includes(availability)) {
              availabilityPresent = true;
            }
          });
          return availabilityPresent;
        })
        .filter((tools) => {
          if (this.selectedTags.length) {
            return this.selectedTags.every((tag) => tools.tags.includes(tag));
          }
          return true;
        });

      return returnData;
    },
  },
  mounted() {
    this.inputPosition =
      this.$refs.input.offsetTop + this.$refs.input.clientHeight;
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
    this.fuse = new Fuse(this.toolsData, {
      keys: [{ name: "name", weight: 2 }, "description", "tags", "license"],
      threshold: 0.2,
      location: 0,
      distance: 10000,
    });
  },
  destroyed() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    setSearchTerm: debounce(function(event) {
      this.search = event.target.value;
      if (event.target.value !== "") this.searchUsed();
    }, 250),
    handleScroll() {
      this.isTop = window.pageYOffset < 250;
      if (window.pageYOffset > this.inputPosition && window.innerWidth <= 600) {
        this.$refs.input.classList.add("sticky");
      } else {
        this.$refs.input.classList.remove("sticky");
      }
    },
    selectTag(tag) {
      if (this.selectedTags.includes(tag)) {
        this.selectedTags = this.selectedTags.filter((item) => item !== tag);
      } else {
        this.selectedTags = [...this.selectedTags, tag];
        this.tagsUsed();
      }
    },
    clearTagSelection() {
      this.selectedTags = [];
    },
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: "smooth" });
    },
    closeSidebar() {
      this.showSidebar = false;
    },
    openSidebar() {
      this.showSidebar = true;
    },
    triggerOpenTool(toolName) {
      const gtag = window.gtag;
      if (gtag) {
        gtag("event", "Open A Tool", {
          event_category: "Click",
          event_label: toolName,
        });
      }
    },
    searchUsed() {
      const gtag = window.gtag;
      if (gtag) {
        gtag("event", "Search", {
          event_category: "Type",
          event_label: "Used",
        });
      }
    },
    tagsUsed() {
      const gtag = window.gtag;
      if (gtag) {
        gtag("event", "Tags", {
          event_category: "Select",
          event_label: "Used",
        });
      }
    },
  },
};
</script>

<style scoped>
.cardContainer {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px;
  height: fit-content;
}
.card {
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(100, 100, 100, 0.1);
  transition: box-shadow ease-in 300ms;
  display: flex;
  flex-direction: column;
}
.card div {
  flex: 1;
}
.card footer {
  flex: unset;
}
.card:hover {
  box-shadow: 0 0 10px rgba(150, 150, 150, 0.35);
}
.tag {
  transition: background-color ease-in 400ms;
  background-color: var(--yellow);
}
.card:hover .tag {
  background-color: var(--yellow-dark);
}

.filterBar {
  margin: 10px;
  box-shadow: 0 0 10px rgba(100, 100, 100, 0.2);
  border: 2px solid var(--yellow);
  border-radius: 5px;
  display: flex;
  text-align: center;
  flex-wrap: wrap;
  background-color: white;
  color: var(--color-black);
}
.filterBar input[type="checkbox"] {
  display: none;
}
.filterBar label {
  display: flex;
  justify-content: center;
  align-items: center;
  user-select: none;
  white-space: nowrap;
}
.filterBar label.active {
  background-color: var(--yellow);
}
.filterBar label svg,
.icon svg {
  margin-right: 5px;
  width: 20px;
  height: 20px;
}

.hero-body {
  padding: 2rem 1.5rem;
}
.subtitle {
  font-style: italic;
}

.scrollToTop {
  position: fixed;
  bottom: 20px;
  right: 20px;
  width: 60px;
  height: 60px;
  font-weight: bold;
  font-size: 2rem;
  color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  border-radius: 50%;
  background-color: var(--yellow);
  box-shadow: 0 0 10px rgba(100, 100, 100, 0.2);
  opacity: 1;
  transition: opacity ease-in 300ms;
}
.top {
  opacity: 0;
}

.section.body {
  display: grid;
  grid-template-columns: 1fr 4fr;
  grid-gap: 20px;
}
@media screen and (max-width: 600px) {
  .section.body {
    grid-template-columns: 1fr;
    position: relative;
  }
  .section.body > .tabsList {
    position: fixed;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    padding: 20px;
    background-color: var(--color-grey);
    z-index: 1;
    overflow: scroll;
    transform: translateX(-100%);
    transition: 250ms ease-in transform;
  }
  .section.body > .tabsList.open {
    transform: translateX(0);
  }
}
@media screen and (min-width: 600px) {
  .filterBar label:hover {
    background-color: var(--yellow);
  }
}

/* Share icons css */
.resp-sharing-button__link,
.resp-sharing-button__icon {
  display: inline-block;
}

.resp-sharing-button__link {
  text-decoration: none;
  color: #fff;
  margin: 0.5em;
}

.resp-sharing-button {
  border-radius: 5px;
  transition: 25ms ease-out;
  padding: 0.25em 0.5em;
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
}

.resp-sharing-button__icon svg {
  width: 1em;
  height: 1em;
  margin-right: 0.4em;
  vertical-align: top;
}

.resp-sharing-button--small svg {
  margin: 0;
  vertical-align: middle;
}

/* Non solid icons get a stroke */
.resp-sharing-button__icon {
  stroke: #fff;
  fill: none;
}

/* Solid icons get a fill */
.resp-sharing-button__icon--solid,
.resp-sharing-button__icon--solidcircle {
  fill: #fff;
  stroke: none;
}

.resp-sharing-button--twitter {
  background-color: #55acee;
}

.resp-sharing-button--twitter:hover {
  background-color: #2795e9;
}

.resp-sharing-button--pinterest {
  background-color: #bd081c;
}

.resp-sharing-button--pinterest:hover {
  background-color: #8c0615;
}

.resp-sharing-button--facebook {
  background-color: #3b5998;
}

.resp-sharing-button--facebook:hover {
  background-color: #2d4373;
}

.resp-sharing-button--tumblr {
  background-color: #35465c;
}

.resp-sharing-button--tumblr:hover {
  background-color: #222d3c;
}

.resp-sharing-button--reddit {
  background-color: #5f99cf;
}

.resp-sharing-button--reddit:hover {
  background-color: #3a80c1;
}

.resp-sharing-button--google {
  background-color: #dd4b39;
}

.resp-sharing-button--google:hover {
  background-color: #c23321;
}

.resp-sharing-button--linkedin {
  background-color: #0077b5;
}

.resp-sharing-button--linkedin:hover {
  background-color: #046293;
}

.resp-sharing-button--email {
  background-color: #777;
}

.resp-sharing-button--email:hover {
  background-color: #5e5e5e;
}

.resp-sharing-button--xing {
  background-color: #1a7576;
}

.resp-sharing-button--xing:hover {
  background-color: #114c4c;
}

.resp-sharing-button--whatsapp {
  background-color: #25d366;
}

.resp-sharing-button--whatsapp:hover {
  background-color: #1da851;
}

.resp-sharing-button--hackernews {
  background-color: #ff6600;
}
.resp-sharing-button--hackernews:hover,
.resp-sharing-button--hackernews:focus {
  background-color: #fb6200;
}

.resp-sharing-button--vk {
  background-color: #507299;
}

.resp-sharing-button--vk:hover {
  background-color: #43648c;
}

.resp-sharing-button--facebook {
  background-color: #3b5998;
  border-color: #3b5998;
}

.resp-sharing-button--facebook:hover,
.resp-sharing-button--facebook:active {
  background-color: #2d4373;
  border-color: #2d4373;
}

.resp-sharing-button--twitter {
  background-color: #55acee;
  border-color: #55acee;
}

.resp-sharing-button--twitter:hover,
.resp-sharing-button--twitter:active {
  background-color: #2795e9;
  border-color: #2795e9;
}

.resp-sharing-button--linkedin {
  background-color: #0077b5;
  border-color: #0077b5;
}

.resp-sharing-button--linkedin:hover,
.resp-sharing-button--linkedin:active {
  background-color: #046293;
  border-color: #046293;
}

.resp-sharing-button--reddit {
  background-color: #5f99cf;
  border-color: #5f99cf;
}

.resp-sharing-button--reddit:hover,
.resp-sharing-button--reddit:active {
  background-color: #3a80c1;
  border-color: #3a80c1;
}

.resp-sharing-button--whatsapp {
  background-color: #25d366;
  border-color: #25d366;
}

.resp-sharing-button--whatsapp:hover,
.resp-sharing-button--whatsapp:active {
  background-color: #1da851;
  border-color: #1da851;
}

.resp-sharing-button--hackernews {
  background-color: #ff6600;
  border-color: #ff6600;
}

.resp-sharing-button--hackernews:hover .resp-sharing-button--hackernews:active {
  background-color: #fb6200;
  border-color: #fb6200;
}

.resp-sharing-button--telegram {
  background-color: #54a9eb;
}

.resp-sharing-button--telegram:hover {
  background-color: #4b97d1;
}

.showOpenSidebar {
  display: none;
  align-items: center;
  padding: 0 10px;
}
@media screen and (max-width: 600px) {
  .showOpenSidebar {
    display: flex;
  }
}

.sticky {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1;
  width: 100%;
  padding: 10px;
  background: white;
  animation: fadeIn 250ms ease-in normal;
  animation-iteration-count: 1;
  color: black;
}
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
