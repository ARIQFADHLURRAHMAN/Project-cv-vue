<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Personal Profile</template>
     <p>
     Saya lahir di Depok,saya saat ini bersekolah di SMK TARUNA BHAKTI Depok.Sebelumnya saya berpengalaman dalam membuat dan mendisain beberapa web. Saya mampu bekerjasecara tim dan individual.
     </p>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    <p>
      2020-2023 <br><a href="https://smktarunabhakti.net/"> SMK TARUNA BHAKTI</a>
    </p>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>

    <ul>
      <li>Weding Invitation Desain</li>
      <li>Hotel Boking Desain</li>
      <li>Web Desain</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Language</template>

    <ul>
      <li>Indonesia</li>
      <li>Engglis</li>
    </ul>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

   
    <p>(+62) 81387052315</p>

    <p>fadhlurrahmanariq51@gmail.com</p>

    <a href="https://github.com/ARIQFADHLURRAHMAN?tab=repositories">Git Hub</a>

  </WelcomeItem>
</template>
