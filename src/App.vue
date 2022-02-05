<template>
  <div class="patch">
    <div class="patch__section">
      <div class="pacth__legend">
        <p>Куда уходит</p>
        <p>Номер порта</p>
        <p>Что сидит</p>
      </div>
      <div class="patch__inner">
        <div class="port" v-for="(port, index) in ports1" :key="index">
          <p>{{ port.destination }}</p>
          <p class="port__number">{{ port.port }}</p>
          <p>{{ port.place }}</p>
        </div>
      </div>
    </div>
    <div class="patch__section">
      <div class="pacth__legend">
        <p>Куда уходит</p>
        <p>Номер порта</p>
        <p>Что сидит</p>
      </div>
      <div class="patch__inner">
        <div class="port" v-for="(port, index) in ports2" :key="index">
          <p>{{ port.destination }}</p>
          <p class="port__number">{{ port.port }}</p>
          <p>{{ port.place }}</p>
        </div>
      </div>
    </div>
    <div class="patch__section rezerv">
      <div class="pacth__legend">
        <p>Куда уходит</p>
        <p>Номер порта</p>
        <p>Что сидит</p>
      </div>
      <div class="patch__inner">
        <div class="port" v-for="(port, index) in ports3" :key="index">
          <p>{{ port.destination }}</p>
          <p class="port__number">{{ port.port }}</p>
          <p>{{ port.place }}</p>
        </div>
      </div>
    </div>
    <div class="patch__section rezerv">
      <div class="pacth__legend">
        <p>Куда уходит</p>
        <p>Номер порта</p>
        <p>Что сидит</p>
      </div>
      <div class="patch__inner">
        <div class="port" v-for="(port, index) in ports4" :key="index">
          <p>{{ port.destination }}</p>
          <p class="port__number">{{ port.port }}</p>
          <p>{{ port.place }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      ports1: [
        {
          port: 1,
          destination: "-",
          place: "-",
        },
        {
          port: 2,
          destination: "-",
          place: "-",
        },
        {
          port: 3,
          destination: "-",
          place: "Лаба",
        },
        {
          port: 4,
          destination: "-",
          place: "-",
        },
        {
          port: 5,
          destination: "-",
          place: "-",
        },
        {
          port: 6,
          destination: "-",
          place: "-",
        },
        {
          port: 7,
          destination: "-",
          place: "104",
        },
        {
          port: 8,
          destination: "-",
          place: "-",
        },
        {
          port: 9,
          destination: "-",
          place: "-",
        },
        {
          port: 10,
          destination: "-",
          place: "-",
        },
        {
          port: 11,
          destination: "-",
          place: "-",
        },
        {
          port: 12,
          destination: "-",
          place: "-",
        },
        {
          port: 13,
          destination: "-",
          place: "-",
        },
        {
          port: 14,
          destination: "-",
          place: "201",
        },
        {
          port: 15,
          destination: "-",
          place: "-",
        },
        {
          port: 16,
          destination: "-",
          place: "204",
        },
        {
          port: 17,
          destination: "-",
          place: "-",
        },
        {
          port: 18,
          destination: "-",
          place: "-",
        },
        {
          port: 19,
          destination: "-",
          place: "-",
        },
        {
          port: 20,
          destination: "-",
          place: "-",
        },
        {
          port: 21,
          destination: "-",
          place: "210",
        },
        {
          port: 22,
          destination: "-",
          place: "REG1(2эт)",
        },
        {
          port: 23,
          destination: "-",
          place: "REG2(2эт)",
        },
        {
          port: 24,
          destination: "-",
          place: "211",
        },
      ],
      ports2: [
        {
          port: 1,
          destination: "-",
          place: "-",
        },
        {
          port: 2,
          destination: "-",
          place: "-",
        },
        {
          port: 3,
          destination: "-",
          place: "214",
        },
        {
          port: 4,
          destination: "-",
          place: "215",
        },
        {
          port: 5,
          destination: "-",
          place: "-",
        },
        {
          port: 6,
          destination: "-",
          place: "-",
        },
        {
          port: 7,
          destination: "-",
          place: "301",
        },
        {
          port: 8,
          destination: "-",
          place: "-",
        },
        {
          port: 9,
          destination: "-",
          place: "305",
        },
        {
          port: 10,
          destination: "-",
          place: "-",
        },
        {
          port: 11,
          destination: "-",
          place: "307",
        },
        {
          port: 12,
          destination: "-",
          place: "-",
        },
        {
          port: 13,
          destination: "-",
          place: "-",
        },
        {
          port: 14,
          destination: "-",
          place: "-",
        },
        {
          port: 15,
          destination: "-",
          place: "-",
        },
        {
          port: 16,
          destination: "-",
          place: "-",
        },
        {
          port: 17,
          destination: "-",
          place: "-",
        },
        {
          port: 18,
          destination: "-",
          place: "-",
        },
        {
          port: 19,
          destination: "-",
          place: "315(ПК)",
        },
        {
          port: 20,
          destination: "-",
          place: "316(ПК)",
        },
        {
          port: 21,
          destination: "-",
          place: "-",
        },
        {
          port: 22,
          destination: "-",
          place: "-",
        },
        {
          port: 23,
          destination: "-",
          place: "-",
        },
        {
          port: 24,
          destination: "-",
          place: "-",
        },
      ],
      ports3: [
        {
          port: 1,
          destination: "-",
          place: "-",
        },
        {
          port: 2,
          destination: "-",
          place: "-",
        },
        {
          port: 3,
          destination: "-",
          place: "Лаба(резерв)",
        },
        {
          port: 4,
          destination: "-",
          place: "-",
        },
        {
          port: 5,
          destination: "-",
          place: "-",
        },
        {
          port: 6,
          destination: "-",
          place: "-",
        },
        {
          port: 7,
          destination: "-",
          place: "-",
        },
        {
          port: 8,
          destination: "-",
          place: "-",
        },
        {
          port: 9,
          destination: "-",
          place: "-",
        },
        {
          port: 10,
          destination: "-",
          place: "-",
        },
        {
          port: 11,
          destination: "-",
          place: "-",
        },
        {
          port: 12,
          destination: "-",
          place: "-",
        },
        {
          port: 13,
          destination: "-",
          place: "-",
        },
        {
          port: 14,
          destination: "-",
          place: "201",
        },
        {
          port: 15,
          destination: "-",
          place: "-",
        },
        {
          port: 16,
          destination: "-",
          place: "204",
        },
        {
          port: 17,
          destination: "-",
          place: "-",
        },
        {
          port: 18,
          destination: "-",
          place: "-",
        },
        {
          port: 19,
          destination: "-",
          place: "-",
        },
        {
          port: 20,
          destination: "-",
          place: "-",
        },
        {
          port: 21,
          destination: "-",
          place: "210",
        },
        {
          port: 22,
          destination: "-",
          place: "REG1(2эт)",
        },
        {
          port: 23,
          destination: "-",
          place: "REG2(2эт)",
        },
        {
          port: 24,
          destination: "-",
          place: "-",
        },
      ],
      ports4: [
        {
          port: 1,
          destination: "-",
          place: "-",
        },
        {
          port: 2,
          destination: "-",
          place: "-",
        },
        {
          port: 3,
          destination: "-",
          place: "-",
        },
        {
          port: 4,
          destination: "-",
          place: "215",
        },
        {
          port: 5,
          destination: "-",
          place: "-",
        },
        {
          port: 6,
          destination: "-",
          place: "-",
        },
        {
          port: 7,
          destination: "-",
          place: "301",
        },
        {
          port: 8,
          destination: "-",
          place: "-",
        },
        {
          port: 9,
          destination: "-",
          place: "305(Р)",
        },
        {
          port: 10,
          destination: "-",
          place: "-",
        },
        {
          port: 11,
          destination: "-",
          place: "307",
        },
        {
          port: 12,
          destination: "-",
          place: "-",
        },
        {
          port: 13,
          destination: "-",
          place: "-",
        },
        {
          port: 14,
          destination: "-",
          place: "-",
        },
        {
          port: 15,
          destination: "-",
          place: "-",
        },
        {
          port: 16,
          destination: "-",
          place: "-",
        },
        {
          port: 17,
          destination: "-",
          place: "-",
        },
        {
          port: 18,
          destination: "-",
          place: "313",
        },
        {
          port: 19,
          destination: "-",
          place: "315",
        },
        {
          port: 20,
          destination: "-",
          place: "316",
        },
        {
          port: 21,
          destination: "-",
          place: "-",
        },
        {
          port: 22,
          destination: "-",
          place: "-",
        },
        {
          port: 23,
          destination: "-",
          place: "-",
        },
        {
          port: 24,
          destination: "-",
          place: "-",
        },
      ],
    };
  },
};
</script>

<style>
body {
  font-size: 12px;
  margin: 0;
  padding: 0;
}

.patch > * {
  display: flex;
  justify-content: space-between;
  height: 20vh;
  padding: 16px;
}

.pacth__legend {
  text-align: center;
  width: 5%;
  padding: 16px 0;
  color: #3c5d70;
  font-weight: bold;
}

.pacth__legend p {
  margin: 0;
  margin-bottom: 36px;
}

.pacth__legend p:first-child { margin-top: 8px; }

.patch__inner {
  display: flex;
  width: 95%;
}

.port {
  width: calc(100% / 24);
  padding: 16px 0;
}

.port p {
  margin: 0;
  margin-bottom: 16px;
  padding: 8px;
  text-align: center;
  color: #282828;
  background-color: hsl(202, 64%, 80%);
}

.port__number {
  font-size: 20px;
}

.rezerv {
  background-color: rgba(22, 193, 67, 0.329);
}

.kommutator {
  display: flex;
  align-items: center;
  justify-content: space-around;
}

@media print {
  .pacth__legend { display: none; }
}

@media print {
  .patch__inner { width: 100%; }
}
</style>
