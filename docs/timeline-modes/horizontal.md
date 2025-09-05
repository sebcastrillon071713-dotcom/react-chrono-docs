import { Card, CardContent } from "@/components/ui/card";
import { Timeline, TimelineItem } from "react-chrono";

export default function LineaTiempoTIC() {
  const items = [
    {
      title: "1837",
      cardTitle: "Telégrafo",
      cardSubtitle: "Permitió la transmisión rápida de mensajes a largas distancias.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/9/9a/Cooke_and_Wheatstone_needle_telegraph.jpg" } },
    },
    {
      title: "1876",
      cardTitle: "Teléfono",
      cardSubtitle: "Revolucionó la comunicación personal y empresarial.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/7/77/Bell%27s_first_telephone.jpg" } },
    },
    {
      title: "1895",
      cardTitle: "Radio",
      cardSubtitle: "Difusión masiva de información y entretenimiento.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/0/0f/Radio_receiver_1930s.jpg" } },
    },
    {
      title: "1946",
      cardTitle: "Computadora ENIAC",
      cardSubtitle: "Primera computadora electrónica de propósito general.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/6/6a/Eniac.jpg" } },
    },
    {
      title: "1969",
      cardTitle: "Internet (ARPANET)",
      cardSubtitle: "Base de la comunicación global moderna.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/d/d2/Arpanet_logical_map%2C_march_1977.png" } },
    },
    {
      title: "1971",
      cardTitle: "Microprocesador (Intel 4004)",
      cardSubtitle: "Permitió la creación de computadoras personales.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/5/55/Intel_C4004.jpg" } },
    },
    {
      title: "1973",
      cardTitle: "Teléfono Móvil",
      cardSubtitle: "Movilidad en la comunicación.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/2/2e/Motorola_DynaTAC_8000X.jpg" } },
    },
    {
      title: "1989",
      cardTitle: "World Wide Web (WWW)",
      cardSubtitle: "Transformó el acceso a la información y la interacción global.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/d/d2/WWW_logo_by_Robert_Cailliau.svg" } },
    },
    {
      title: "2004",
      cardTitle: "Redes Sociales (Facebook)",
      cardSubtitle: "Cambió la forma de socializar, informarse y hacer negocios.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/c/c2/F_icon.svg" } },
    },
    {
      title: "2022",
      cardTitle: "Inteligencia Artificial (IA Moderna)",
      cardSubtitle: "Automatización avanzada, asistencia virtual y cambios en educación y trabajo.",
      media: { type: "IMAGE", source: { url: "https://upload.wikimedia.org/wikipedia/commons/3/3a/Artificial_intelligence_brain.png" } },
    },
  ];

  return (
    <div className="p-6">
      <h1 className="text-3xl font-bold text-center mb-6">Línea de Tiempo: Evolución de las TIC</h1>
      <Card className="shadow-lg rounded-2xl">
        <CardContent>
          <Timeline items={items} mode="VERTICAL_ALTERNATING" />
        </CardContent>
      </Card>
    </div>
  );
}
