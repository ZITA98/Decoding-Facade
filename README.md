# Decoding the Singapore Shophouse
## Overview

Through visual intelligence technologies, this repository implements a computational framework for systematically analyzing vernacular architecture --- Singapore Shophouse. The framework augments traditional intuitive analysis by applying machine learning to identify formal patterns, classification hierarchies, and evolutionary relationships in historical buildings.

This repository contains a building analysis system with four key components:

1. **ResNet-50 Façade-based Cultural Classification** - Initial classifier for cultural analysis across four historical districts using façade imagery and ImageNet pre-trained weights

2. **Grad-CAM Visualization** - Provides visual explanations for classification decisions

3. **YOLOv5 Building Component Detection** - Detects and localizes architectural components

4. **Phylogenetic Analysis** - Constructs evolutionary relationships using external software (PAST 4.17 & SplitsTree6 6.4.7) with provided workflows and interface scripts
