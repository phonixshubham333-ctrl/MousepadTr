I Change minor to change the Placeholdersize add css these lines 
.design-container {
  width: 23cm;
  height: 19cm;
  max-width: 100%;
  border: 2px dashed #a78bfa;
  background-color: #f5f3ff;
  border-radius: 10px;
  margin: 0 auto;
  position: relative;
  overflow: hidden;
}
and this 
@media (max-width: 768px) {
  .design-container {
    width: 100%;
    height: auto;
    aspect-ratio: 23 / 19;
  }
}
