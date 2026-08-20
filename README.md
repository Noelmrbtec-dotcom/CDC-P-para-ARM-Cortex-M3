# CDC-P v3.1 - Um Cyber Organismo com Previsibilidade Absoluta

## Um sistema que transcende a definição de RTOS. Ele respira, tem reflexos, se adapta, se cura, se defende e, se tudo falhar, renasce. Tudo em 17.6 KB de ROM e 7.0 KB de RAM.

[![Platform](https://img.shields.io/badge/platform-Cortex--M3-blue)](https://www.st.com/en/microcontrollers-microprocessors/stm32f103c8.html)
[![ROM](https://img.shields.io/badge/ROM-17.6%20KB%20(26.9%25)-green)]()
[![RAM](https://img.shields.io/badge/RAM-7.0%20KB%20(35.1%25)-brightgreen)]()
[![Clock](https://img.shields.io/badge/Clock-72%20MHz-blue)]()
[![Overhead](https://img.shields.io/badge/Overhead-0.16%25%20CPU-orange)]()
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

---

## Visão Geral

O CDC-P (Concurrency Deterministic Control with Preemption) não é um RTOS tradicional. É um **Cyber Organismo com Previsibilidade Absoluta** — um sistema que exibe funções análogas às biológicas no domínio temporal.

Diferentemente de RTOS preemptivos como FreeRTOS e ThreadX, o CDC-P não usa preempção interruptiva. Em vez disso, respira (tick dinâmico), tem reflexos (URG-S), se adapta ao ambiente (auto-regulagem), se cura de feridas (Task9), se defende de ameaças (Task10 com isolamento permanente) e, se tudo falhar, renasce (reset_cpu). E tudo isso é 100% previsível, 100% determinístico, 100% comprovado em hardware real.

O sistema é imune a condições de corrida, deadlocks e inversão de prioridade por construção arquitetural, não por mecanismos de correção posteriores. Utiliza apenas 26.9% da ROM (17.6 KB) e 35.1% da RAM (7.0 KB) em um STM32F103C8T6 (Cortex-M3) rodando a 72 MHz.

> *"A simplicidade é um pré-requisito para a confiabilidade."* — Edsger W. Dijkstra

---

## O Cyber Organismo

| Função Biológica | Equivalente no CDC-P | Mecanismo |
|:---|:---|:---|
| Respiração | Tick dinâmico | Ajusta frequência do sistema conforme a demanda (1ms a 50ms) |
| Reflexos | URG-S | Resposta imediata e involuntária a estímulos externos (mesma iteração) |
| Homeostase | Auto-regulagem | Mantém equilíbrio temporal sob carga variável |
| Cicatrização | Task9 (Síndico) | Recupera tarefas bloqueadas progressivamente |
| Sistema Imunológico | Task10 (Xerife) + pane_taskX | Detecta e isola ameaças permanentemente |
| Renascimento | reset_cpu() | Reinicia o organismo quando tudo falha |
| Evolução | Dimensionamento experimental | Aprende o WCET real de cada tarefa |

**Previsibilidade Absoluta:** Não há "depende". Não há "às vezes". Não há "em algumas condições". Cada função ocorre de forma previsível e reproduzível. Sempre.

---
